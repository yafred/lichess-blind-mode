---
layout: page
title: What's new
permalink: /changelog
---


## What's New in Blind Mode

The following section highlights the latest changes and improvements made to Lichess's blind mode, also known as the non-visual user interface (NVUI). It is intended for users who are already familiar with how NVUI works and want to stay up to date with ongoing enhancements. Whether it's a new feature, a bug fix, or a small accessibility improvement, each item is listed with a brief description and a link to the relevant pull request for those interested in technical details. The most recent updates appear at the top of the list, making it easy to check what's new. You can skip to the next heading to begin reading the tutorial.

* **made “Learn from Your Mistakes” fully accessible in blind mode:**

  * All elements of the feature—including **mistake prompts**, **feedback**, and **move suggestions**—are now announced properly by screen readers.
  * Added support for:

    * Reviewing **both sides' mistakes** with auto-board flip
    * Clear **confirmation of analysis requests**
    * **Proper sequencing** of prompts and responses
  * This major upgrade allows blind players to use **Learn from Your Mistakes** independently and intuitively for the first time.
    **[PR #17739](https://github.com/lichess-org/lila/pull/17739)**

* **adding the ability to flip board, and ensured consistency of blind mode commands across gameplay, analysis, and puzzle views:**

  * The `X` and `Alt + X` **ray scanning commands** now work the same way in **puzzle** and **analysis** modes.
  * Pressing `F` flips the board in all views, including analysis and puzzle.
    (Note: you will receive a message indicating that the board is flipped)
  * Improved behavior of the **`B` command**:
    When returning from the board to input form and back again, `B` now jumps to the **last active square**, not the default e4.
  * These refinements make blind mode more predictable and fluid across all site areas.
    **[PR #17784](https://github.com/lichess-org/lila/pull/17784)**

* **added keyboard shortcut `V` to announce computer evaluation in blind mode:**

  * While focused on the **chessboard**, pressing `V` now announces the **current computer evaluation** (e.g., “Evaluation: +0.8”).
  * This feature brings evaluation access directly to the board, instead of requiring navigation to the analysis panel.
  * Helps blind players quickly check who is better without leaving their position on the board.
    **[PR #17795](https://github.com/lichess-org/lila/pull/17795)**

*  **fixed NVDA screen reader issues in gameplay, analysis, and puzzles:**

  * Blind mode announcements (like evaluation, input commands, and move list navigation) are now **properly spoken again** by NVDA, especially on Firefox.
  * Solved a critical issue where focus was being reset to the page body after certain DOM updates, breaking screen reader feedback.
  * Now users reliably hear:

    * **Mistake messages** in “Learn from your mistakes”
    * **Computer evaluation output**
    * **Board navigation cues**
  * This makes blind mode much more **stable and predictable** for Windows NVDA users across the site.
    **[PR #17831](https://github.com/lichess-org/lila/pull/17831)**

* **enhanced blind mode announcements for board navigation and status keys:**

  * Pressing the **`O` key** now announces both the square and the piece on it (e.g., “A1 white rook”) instead of just “A1”.
  * This change brings **consistency** with arrow-key navigation, where square and piece are already announced together.
  * The internal handling of board events was also **refactored**, paving the way for more reliable feedback in blind mode.
    **[PR #17827](https://github.com/lichess-org/lila/pull/17827)**

* **added direct link to the blind mode tutorial on the homepage:**

  * First-time screen reader users now hear:
    **“Accessibility – Enable blind mode – link: Blind mode tutorial”**
    at the top of the homepage.
  * Pressing `K` for links lets users **quickly navigate** to the tutorial without enabling blind mode first.
  * This change improves **discoverability** of blind mode instructions while keeping the **accessibility toggle behavior unchanged**.
    **[PR #17823](https://github.com/lichess-org/lila/pull/17823)**

* **the ability to read ranks, files and diagonals:
  * while focused on any square on the board, `x` scans **diagonal** rays clockwise, starting from **top-right**.
  * `Alt + x` scans **vertical and horizontal** rays clockwise, starting from **top**.
  * Holding `Shift` reverses the direction (counter-clockwise).
  * Repeating the same command continues to the **next ray** in the sequence.
  * Users can **freely mix** `x` and `Alt + x` while staying on the same square.
    This expands spatial awareness and gives more flexible scanning options to blind mode users.
    **[PR #17701](https://github.com/lichess-org/lila/pull/17701)**
* **Announce Pieces by Color:** The `p` (piece) command now supports announcing pieces by color using a pseudo-piece symbol:
  - `p a` announces the location of all **black** pieces.
  - `p n` announces the location of all **black** knights.
  - `P A` announces the location of all **white** pieces.
  - `P N` announces the location of all **white** knights.
  This allows blind mode users to quickly scan the board for pieces of a specific color.  
  **[PR #17687](https://github.com/lichess-org/lila/pull/17687)**

* **Puzzle Board Navigation Restored:** Refactored the puzzle board to restore full keyboard navigation in blind mode:  Users can now move around the board using arrow keys while solving puzzles. **[PR #17664](https://github.com/lichess-org/lila/pull/17664)**

* **Case-Insensitive Drops/Promotions:** Blind mode now accepts capital letters for piece notation in Crazyhouse drops and pawn promotions. For example, entering a drop as “N\@f3” or a promotion as “e1=Q” will work (previously NVUI might have only accepted lowercase “n\@f3” or “e1=q”). This makes input more forgiving and intuitive for those accustomed to uppercase piece letters. **[PR #17650](https://github.com/lichess-org/lila/pull/17650)**

* **Layout Order Setting:** Added an option in blind mode, found under the board settings,  to choose the order of “Actions” vs “Board” on the game page. Users can now toggle whether the action buttons (resign, offer draw, etc.) are displayed  before the board or after it, according to their preference, rather than being in a fixed order. **[PR #17573](https://github.com/lichess-org/lila/pull/17573)**

* **Consistent Clock Speech:** The clock announcement feature now uses the same verbal time format introduced in the UI for its spoken output. This refactor means when blind mode “speaks” the clock, it uses the translated, human-friendly format (e.g. “5 minutes 30 seconds”) instead of a raw numeric format, keeping speech and display consistent. **[PR #17473](https://github.com/lichess-org/lila/pull/17473)**

* **Better Board Focus Description:** Improved the description announced when the chessboard receives focus in NVUI. Instead of just reading coordinates, the screen reader will now say “Square \[coordinate]” which provides more context (for example, hearing “Square e4” rather than just “e4”). **[PR #17510](https://github.com/lichess-org/lila/pull/17510)**

* **Localized “Ongoing Games” in Lobby:** The blind mode lobby now uses translated text for the “ongoing games” section. Previously this label was not internationalized; now it reuses existing translations for consistency, so users in all languages will see a properly translated phrase. **[PR #17562](https://github.com/lichess-org/lila/pull/17562)**

* **Punctuation for Move Announcements:** Added punctuation to moves in NVUI to aid screen reader pauses. This small change improves how moves are spoken by text-to-speech, ensuring there’s a clear break (for example, after a move is read aloud) so the audio is more understandable. **[PR #17465](https://github.com/lichess-org/lila/pull/17465)**

* **Internationalized Input Commands:** Made blind mode input commands translatable. NVUI commands (like “takeback” or “draw”) are now integrated with Lichess’s i18n system, so they can be typed and recognized in the user’s language and their descriptions are shown in the correct locale. **[PR #17615](https://github.com/lichess-org/lila/pull/17615)**

* **Improved Layout for Game Page:** The blind mode game (round) page layout was reorganized for easier navigation:
  - The move input form is now placed directly next to the board, allowing quicker navigation between entering moves and hearing board state.
  - Tooltips on action buttons were removed to prevent redundant screen reader output (e.g., “resign button… resign”).
  - Quick keyboard commands were added:
    - Typing `"board"` focuses the board.
    - Typing `"i"` focuses the input field.  
  **[PR #17452](https://github.com/lichess-org/lila/pull/17452)**

* **Verbal Clock Announcements:** Blind mode now renders clock times as spoken text rather than as digits. For example, a clock showing “01:30” will be announced as “1 hour, 30 minutes” instead of “01 colon 30”. This unification (used in both game and analysis) helps screen readers and uses existing translations for time units. **[PR #17442](https://github.com/lichess-org/lila/pull/17442)**

* **Sorted ‘Scan’ Command Output:** The blind mode “scan” command (which lists pieces on the board) now outputs in a sorted, consistent order. This makes it easier for visually impaired users to parse the list of pieces without a confusing order. **[PR #17190](https://github.com/lichess-org/lila/pull/17190)**

* **Game Status in broadcasts and Study Mode:** Blind mode will now announce or display the game result/status when viewing a study chapter. Previously, results (like checkmate or draw) in study replays were missing – now the NVUI shows these outcomes, partially addressing that issue. **[PR #17312](https://github.com/lichess-org/lila/pull/17312)**

* **Broadcast Navigation Controls:** Introduced accessible navigation for broadcasts in blind mode. NVUI now provides dropdowns/combo boxes to switch between broadcast groups, rounds, and games, allowing visually impaired users to navigate multi-game broadcasts. It also improved focus handling (auto-focusing the new selection) so screen readers don’t reset to the top of the page. **[PR #17341](https://github.com/lichess-org/lila/pull/17341)**

* **Unusual Results Announced:** Added support for “unusual” game results in blind mode broadcasts and studies. Beyond standard checkmates or draws, NVUI will now also announce special outcomes (e.g. time outs, aborts, etc.), ensuring all game results are conveyed to the user. **[PR #17347](https://github.com/lichess-org/lila/pull/17347)**

* **Chat in Analysis NVUI:** The chat room is now included in the blind mode analysis/study page. NVUI adds the chat at the end of the page, so blind users can read and participate in study or broadcast chat using their screen reader. **[PR #17387](https://github.com/lichess-org/lila/pull/17387)**

* **Tournament Info and Players List:** Tournament pages in blind mode now show tournament details and the player list (loaded lazily for performance). The tournament info is placed at the bottom of the NVUI page, making sure blind users can access standings and participants in an “immersive” way via screen reader. **[PR #17401](https://github.com/lichess-org/lila/pull/17401)**

* **“Copy FEN” Button:** Added an accessible “Copy FEN” button in analysis mode for blind users. In NVUI, users can now copy the FEN of the current position with a single button press, addressing a missing feature in the analysis board for blind mode. **[PR #17407](https://github.com/lichess-org/lila/pull/17407)**

* **Crazyhouse Support in Blind Mode:** Blind mode now supports the Crazyhouse variant. This update allows blind users to play Crazyhouse (with piece drops) and includes code clean-ups like better input handling and fixes for selection issues in NVUI. **[PR #16997](https://github.com/lichess-org/lila/pull/16997)**

* **Choose Color in Blind Mode:** Restored the option for a blind mode player to select their own color when creating a game (a feature that had been lost in a regression). Blind users can again choose to play as White or Black instead of being forced into random color. **[PR #17017](https://github.com/lichess-org/lila/pull/17017)**

* **Board Fully Visible on Small Screens:** Ensured the entire 8×8 board is displayed in blind mode even on small screens. Squares now scale to 1/8 of the screen width (or of 500px on larger screens) so that no ranks/files are cut off in NVUI. This works mostly on landscape orientation. **[PR #17025](https://github.com/lichess-org/lila/pull/17025)**

* **Input Disambiguation Fix:** Fixed an issue with blind mode move input where ambiguous moves weren’t handled properly. This resolves problems entering moves that require disambiguation (such as two identical pieces moving) so that NVUI recognizes them correctly. **[PR #17142](https://github.com/lichess-org/lila/pull/17142)**

* **Various NVUI Improvements:** A collection of tweaks added multiple blind mode features:
  - Fixed the display of player info in studies and broadcasts.
  - Added keyboard commands to jump to next/previous moves or variations while focusing on the board: shift + a and shift + d to navigate moves, alt + shift + a and alt + shift + d to navigate lines.
  - Clock announcements now work in studies and broadcasts.
  - Added combo Box  to switch between different broadcast games more easily.  
  **[PR #16864](https://github.com/lichess-org/lila/pull/16864)**

* **Fixed Blind Mode in Broadcasts:** Resolved a bug that caused the blind mode  to crash during broadcast games. This fix ensures blind mode works correctly when viewing live broadcasts. **[PR #16856](https://github.com/lichess-org/lila/pull/16856)**
