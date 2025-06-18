---
layout: page
title: Tutorial
permalink: /tutorial
---

## Introduction

Welcome to the **Lichess Blind Mode Tutorial** — a practical guide designed for **blind and visually impaired players** using screen readers to enjoy chess on [lichess.org](https://lichess.org).

Lichess is one of the most accessible chess platforms available today. Its built-in **Blind Mode** transforms the interface into a fully keyboard-navigable and screen reader-friendly environment, enabling users to:

* Play games against the computer or other players
* Analyze games using a powerful chess engine
* Join teams and tournaments
* Solve puzzles and study positions
* Interact with ongoing broadcasts of top-level games

This guide aims to:

* Help you get started with Blind Mode
* Explain how to navigate and interact with the site using screen readers like **NVDA**, **JAWS**, **VoiceOver**, and **Orca**
* Introduce keyboard shortcuts and commands for efficient gameplay
* Highlight key features and known limitations
* Suggest workarounds and offer troubleshooting tips

> ⚠️ **Note:** Lichess is a large and continuously evolving platform. While this guide aims to cover as many relevant features as possible for blind users, it is not intended to be fully comprehensive. Given the wide range of tools and frequent updates, some areas may not be included or may require future expansion. We encourage readers to explore beyond this tutorial and contribute suggestions for future revisions.

We also want to express our appreciation to the **Lichess development team** for their ongoing efforts to make the platform more accessible. Their responsiveness to feedback and collaboration with blind users have played a key role in shaping a more inclusive experience.

If you encounter any bugs or accessibility issues, please refer to the **“Reporting Issues and Feedback”** section at the end of this guide. Your input helps improve the platform for everyone.

Let’s begin!

---

## 1. Navigating Lichess Using a Screen Reader

Using Lichess in Blind Mode depends heavily on knowing how to switch between **Browse Mode** and **Focus Mode** (also known as Forms Mode or Interaction Mode). Understanding when to use each mode is key to navigating the site efficiently.

### 1.1 Browse Mode vs Focus Mode

Screen readers offer two main ways to interact with websites:

* **Browse Mode (also called Virtual Cursor or Reading Mode):**
  Allows you to read the content of the page using navigation keys (like `H` for headings or `B` for buttons). Use this mode to **explore the page, read game history, navigate menus, or find links and settings**.

* **Focus Mode (also called Forms or Interaction Mode):**
  Sends your keystrokes directly to a form field or interactive element. Use this when you need to **type in the move input field, adjust game settings, or interact directly with the chessboard**.

 Switching between these two modes is essential. A common pattern is:

 * **Browse Mode to find and open a form**
 * **Switch to Focus Mode to type or interact**

### 1.2 Navigation Keys: Windows (NVDA / JAWS)

These keys work in **Browse Mode**, which is active by default when a page loads.

* **Toggle Browse / Focus Mode:**
  `NVDA + Space` (for NVDA) or `Insert + Z` (for JAWS)

* **Go to the top of the page:**
  `Ctrl + Home`

* **Move to the next heading:**
  `H`

* **Move to heading level 1–6:**
  Press the number keys `1` through `6` to jump to corresponding heading levels

* **Jump to the next button:**
  `B`

* **Jump to the next edit field:**
  `E`

* **Find text on the page:**
  `NVDA + Ctrl + F` or `JAWS key + Ctrl + F`

 **Tip:** Holding **Shift** with any of these navigation keys **reverses the direction** (e.g., `Shift + H` moves to the previous heading).

### 1.3 Navigation Keys: macOS (VoiceOver)

VoiceOver offers two ways to navigate:

* With **QuickNav enabled**, you can use single-letter keys similar to Windows screen readers.
* With **QuickNav disabled**, you use **VO + Command + key** combinations.

* Toggle QuickNav: `VO + Q`

#### Navigation Shortcuts (QuickNav On)

* **Next heading:**
  `H`

* **Jump to heading level 1–6:**
  Press `1` to `6` for heading levels 1 through 6, or `Shift + 1` to `6` to move backward

* **Next button:**
  `B`

* **Next edit field:**
  `E`

#### Navigation Shortcuts (QuickNav Off)

* **Next heading:**
  `VO + Command + H`

* **Next button:**
  `VO + Command + B`

* **Next edit field:**
  `VO + Command + J`

* **Go to the top of the page:**
  `VO + Fn + Left Arrow` 

* **Find text on the page:**
  `Command + F`

 **Tip:** Holding **Shift** with any of these navigation keys **reverses the direction** (e.g., `Shift + H` moves to the previous heading).

 Use the method that works best for you. QuickNav is often more convenient for fast navigation, while VO+Command combos offer more control when QuickNav is off.

### 1.4 Using Tab and Arrow Keys

While navigation keys like `H`, `B`, and `E` are powerful, sometimes the simplest keys — **Tab** and **Arrow Keys** — are the most reliable.

* **Tab / Shift + Tab:** Move between **interactive elements** (like buttons, edit fields, and links). Useful for moving through forms and settings.
* **Arrow keys (Up/Down):** Scroll through the page line by line in **Browse Mode**. This helps with reading instructions or game logs.

> ⚠️ Be cautious: using Tab alone may skip over important content. Use **Arrow Keys** in Browse Mode to explore thoroughly.

---

## 2. Getting Started

### 2.1 Requirements and Recommendations

To use Lichess effectively in Blind Mode, you’ll need:

* A **screen reader**, such as:

  * [NVDA (Windows)](https://nvaccess.org)
  * [JAWS (Windows)](https://www.freedomscientific.com/Products/software/JAWS/)
  * [VoiceOver (macOS/iOS)](https://support.apple.com/guide/voiceover/welcome/mac)
  * [Orca (Linux)](https://wiki.gnome.org/Projects/Orca)
* A **modern web browser**, like Chrome, Firefox, Safari, or Edge
* A **stable internet connection**
* Familiarity with **keyboard navigation** on the web

> ⚠️ If you're using Lichess on a **mobile device**, we recommend connecting a **Bluetooth or wired keyboard**. While the touch screen interface is partially usable, the current experience is not yet fully optimized for screen reader users on mobile without a physical keyboard.

Although it's possible to play anonymously, **creating a free account** is highly recommended. This allows you to track your games, ratings, preferences, and access advanced features like tournaments, studies, and team play.

### 2.2 Enabling Blind Mode

**Blind Mode** is a special accessibility feature on Lichess that adapts the entire website for screen reader users. When enabled, it:

* Simplifies the page layout to remove visual clutter
* Presents information in a logical, linear structure
* Provides auditory feedback for game events and actions
* Enables keyboard shortcuts and command-based interaction with the chessboard

In short, Blind Mode transforms Lichess into a screen-reader-friendly environment that makes playing and navigating fully accessible without using a mouse.

To enable it:

1. Open [lichess.org](https://lichess.org)
2. Your screen reader should already be in **Browse Mode** by default (if not, enable it: NVDA+Space, Insert+Z in JAWS, or turn off QuickNav in VoiceOver)
3. Press **Ctrl+Home** (Windows) or **VO+Fn+Left** (Mac) to go to the top of the page
4. Use the **Down Arrow** to reach the button labeled:
   **"Accessibility: Enable blind mode"**
5. Press **Enter** or **Space** to activate it
   Once active, the label will change to **"Accessibility: Disable blind mode"**

  Once you enable Blind Mode while signed in, Lichess will remember your preference. It will stay active automatically every time you visit the site, without needing to turn it on again.

### 2.3 Signing In or Creating an Account

To sign in or register for a free account:

1. Press the **Down Arrow** repeatedly until you reach the **“Sign in”** link.
   Alternatively, you can use the **find feature** on your screen reader by pressing **NVDA+Ctrl+F** (or Command+F on Mac) and type *sign in* to locate it quickly.
2. Press **Enter** to open the login page
3. If you already have an account, enter your **username** and **password**, then press **Enter** to log in.

If you're new to Lichess, select **“Register”** to create an account. You’ll be asked to fill out a simple form with the following:

* A **username**: Choose something appropriate and family-friendly. It **cannot be changed later**, and accounts with offensive names may be closed.
* A **password**: Lichess will provide feedback on password strength as you type.
* An **email address**: This is optional but highly recommended, as it allows you to reset your password if needed.

Before completing registration, you must:

* **Agree** not to use chess engines, books, databases, or help from other people during games.
* **Agree** to be respectful toward other players.
* **Agree** not to create multiple accounts unless allowed by the Terms of Service.
* **Agree** to follow all Lichess rules and policies.
* **Check the “I am human” box** to confirm you're not a bot (this uses **hCaptcha**, which is partially accessible and offers options for visually impaired users).

Registration is completely free and takes just a minute. Once completed, you can start playing right away — **no email verification is required** to activate your account.

#### A Note on hCaptcha Accessibility

During registration, Lichess uses **hCaptcha** to confirm that you're human. This is a common security measure to prevent spam or automated account creation.

While hCaptcha is not fully accessible by default, it does offer an **accessibility mode** for screen reader users. If your browser has the **accessibility cookie** set, the challenge may be skipped automatically or presented in a more accessible way.

If you're using a screen reader and encounter difficulty:

* Look for a link or button labeled **"Accessibility options"** or **"I am human"**.
* You may be redirected to [hcaptcha.com/accessibility](https://www.hcaptcha.com/accessibility) to register your browser for enhanced access.

 Once registered, hCaptcha should remember your device and make future challenges easier to complete.

If you continue to have issues, you can temporarily ask a sighted person for help just with the captcha step. After that, Lichess itself is fully accessible and can be used independently.

---

## 3. Playing a Game

Lichess offers several ways to start a game. You can play against anyone in the world, challenge a friend, or play against the computer — all fully accessible with a screen reader.

### 3.1 Creating a Game with the Community

At the **top of the Lichess homepage**, you'll find a link labeled **"Create a game"**. This opens a dialog that lets you create a public game and wait for another Lichess user to join.

Once you activate that link, you can customize the following options:

#### Variant

Use the arrow keys or Tab to navigate to the **variant selector**. Lichess supports several chess variants, all of which are accessible using screen readers. Here's a list of the available options:

* **Standard**
  The traditional version of chess played worldwide. Most players choose this variant.

* **[Chess960 (Fischer Random)](https://lichess.org/variant/chess960)**
  The back-rank pieces are shuffled randomly. There are 960 possible starting positions.

* **[King of the Hill](https://lichess.org/variant/kingOfTheHill)**
  A player wins by bringing their king to one of the four center squares (d4, e4, d5, or e5).

* **[Three-check](https://lichess.org/variant/threeCheck)**
  You win by checking your opponent **three times**. Checkmate is not required.

* **[Antichess](https://lichess.org/variant/antichess)**
  Captures are mandatory. The goal is to lose all your pieces or get stalemated.

* **[Atomic](https://lichess.org/variant/atomic)**
  Captures cause explosions, removing surrounding pieces. Kings can't be next to each other.

* **[Horde](https://lichess.org/variant/horde)**
  One side has a full army, the other has a "horde" of pawns. The pawn side moves first.

* **[Racing Kings](https://lichess.org/variant/racingKings)**
  There are no checks. The first player to bring their king to the 8th rank wins.

* **[Crazyhouse](https://lichess.org/variant/crazyhouse)**
  When you capture a piece, it joins your reserves. You can place it back on the board as your own.

 We recommend starting with **Standard** chess before exploring the other variants, especially if you are new to Blind Mode or online chess.

> 🛈 **Note:** To select a variant using the **arrow keys**, your screen reader must be in **Focus Mode**. If you're in **Browse Mode**, the arrow keys will simply move you down the page rather than changing the selection. Some screen readers, like NVDA and JAWS, may enter Focus Mode **automatically** when you reach an interactive control like a combo box or edit box — this behavior depends on your settings. Be sure to **listen for the sound or spoken feedback** that indicates you're entering or exiting Focus Mode, so you know when it's safe to use the arrow keys for selection.

#### Time Control

Next, you’ll choose how time is managed during the game. Use Tab or arrow keys to select one of the following modes:

* **Real Time:** A countdown clock is used. After selecting this, you’ll set:

  * **Minutes per side**: how many total minutes each player has
  * **Increment**: how many seconds are added after each move

* **Correspondence:** Games are played over hours or days. Ideal for slower, thoughtful play.

* **Unlimited (No Clock):** There is no time limit. Great for casual or teaching games.

####  Casual vs Rated

Next, you’ll tab to a **radio button** asking whether this game is:

* **Casual:** The result does **not affect your rating**
* **Rated:** The game will **affect your Lichess rating**, depending on the result

> 🛈 You must be logged in to play rated games.

Once all parameters are selected, press **Tab** to reach the **"Create game"** button and press **Enter**. Your game request will be sent to the **Lichess lobby**, where it will be matched with the first available player who accepts the challenge. For instance, if you set your game to 30 minutes with a 30 second increment, you will attract players that like a bit of a longer game. Depending on the parameters, it might take a few minutes for another player to play your game, but the system will let you know when the game has been accepted by another player. Generally however, someone will accept your game very quickly, usually less than a minute.

### 3.2 playing with friends

Alternatively, if you navigate **down the homepage** to **heading level 2 labeled “Play”**, you’ll find three main options:

the first is called **Create a Game**. This option works the same as the "Create a game" link at the top of the page.

The second choice is **play with a friend**. In addition to creating a public game, Lichess also allows you to **challenge a specific player** — such as a friend, a coach, or someone whose username you know. When you choose **“Play With a Friend”**, a dialog box opens where you can configure the same settings as before (variant, time control, rated or casual), with an additional option where you can choose which **side** you want to play (White, Black, or Random). After configuring these game settings, you press the **“Create Game”** button.

This brings you to a new page where you have multiple ways to invite someone:

* **Search for a specific username** using the **search field**:
  After creating the challenge, you’ll land on a page with a search box. You can type in the Lichess username of the person you'd like to play with. As you type, matching usernames will appear. Use the arrow keys to select the correct one and press Enter to send them the challenge directly. This is ideal when you already know who you want to play with. The challenge will reach this person where they can accept or deny. If they accepted your challenge, the game screen will open with the white player ready to make their first move.

* **Pick from a list of previous opponents** you’ve played with before, shown just above the search:
  If you’ve played games on Lichess in the past, the system remembers those players. Above the search field, you’ll find a list of usernames you've recently played with. You can navigate through this list using the arrow keys and choose one to re-challenge easily — no need to retype or search their name again.

* **Copy the game link** by pressing the **“Copy URL”** button:
  This button copies a special link to your clipboard. You can paste it anywhere — in an email, a messaging app, or even a group chat — using **Ctrl + V**. The first person who clicks on this link will become your opponent and join the game. This method is great when you want to leave the challenge open for anyone interested or don’t want to target a specific user.

* **Cancel the challenge** if you change your mind:
  If you decide not to send the challenge after all, just press the **“Cancel”** button. This will close the invitation and take you back to the previous screen without sending any challenge.

#### Accepting a Challenge

If someone sends you a challenge, and you're currently on the Lichess website, a **pop-up window** will appear with a **sound notification**. The window will show:

* The **challenger's name**
* The **variant**
* The **time control**
* Whether the game is **rated or casual**

You will find two buttons:

* **Accept** – The game starts immediately.
* **Decline** – If you don’t want to play, you can decline. Below this button is a combo box where you may optionally select a reason for declining.

#### Finding Missed Challenges

If you're not on Lichess at the moment the challenge was sent — or if the pop-up doesn’t appear — you can still check your **pending challenges** manually.

From the **main page**:

1. Press **E** to jump to the search field.
2. Arrow down — if you have a challenge, a number will appear here.
3. Press **Space** on that number. (Even if it’s not labeled as a link, it works.)
4. This opens the challenge details, where you can then choose **Accept** or **Decline**.

3.3 Play with the Computer

Choose this option to play against a Lichess chess engine.

You’ll be able to:

* Choose the **variant**
* Select the **engine difficulty**, from **1** (beginner) to **8** (very strong)
* Set your **side**: White, Black, or Random

Once you finalize your choices, press the **Create game** button, and the game will begin instantly.

---

## 4. making moves

For demonstration purposes, let’s begin by creating a simple game against the computer:

* Go to **"Play with the computer"**
* Choose the **Standard** variant
* Set the **time control to Unlimited**
* Choose to play as **White**

This setup gives us all the time we need to practice without pressure.

Once the game is created, your screen reader may automatically place **focus** in a text field labeled something like:

> `"Your move, edit field"` or `"Command input"`

This field is where you will enter your **chess moves** or **keyboard commands**. It is commonly referred to as the **Command Input Field**.

Depending on your screen reader settings:

* You may automatically enter **Focus Mode**
* Or you may need to **manually switch to Focus Mode** to start typing (e.g., `NVDA + Space`, `Insert + Z`, or turning off QuickNav)

We will explore this input field in more detail in the next section, but for now, let's look at what else appears on the page.

### 4.1 Page Structure and Headings

Lichess pages are organized using **headings**. When a game starts, the **main content** of the page begins with a **Heading Level 1**. When you are at the top of the page, pressing the number `1` in Browse Mode will take you straight there.

Here’s a breakdown of what you’ll find as you move through the page using the `H` key:

####  Heading Level 1: Game Title

**Example:**
`You play the white pieces Casual correspondence Game vs Stockfish level 1`

This heading confirms:

* Your color (White or Black)
* The type of game (Casual or Rated)
* The time control (Real time, Correspondence, Unlimited)
* Your opponent (e.g., Stockfish level 1, or another player)

#### Heading Level 2: Game Info

Displays player names and ratings:
**Example:**

```
White: YourUserName  1500  
Black: TheirUserName 1556 
Casual correspondence  
```

#### Heading Level 2: Move List

As the game progresses, moves are added to this list. It starts empty and updates after each move.
Use arrow keys or `Down Arrow` in Browse Mode to read through them.

#### Heading Level 2: Pieces

This section lists the locations of all pieces on the board in plain language.
It’s broken down by player:

* **Heading Level 3: White**
  Example:
  `King: eva 1, Queen: david 1, Rooks: anna 1, hector 1, …`

* **Heading Level 3: Black**
  Same structure for Black’s pieces.

 This section is especially helpful for screen reader users to get a quick overview of the current position without using the board navigation.

#### Heading Level 2: Game Status

Indicates the current state of the game:

* **"Playing right now"**
* Could later change to "white wins by checkmate", "Draw", etc.

#### Heading Level 2: Last Move

Announces the last move played in plain text.
At the start of the game, this will say "Game start", and will update after each move.

#### Heading Level 2: Input Form

This is where the **command input field** is located — where you type your moves like `e4`, or commands like `C` for clocks.
We'll explore this in detail in the **next section**.

#### Heading Level 2: Clocks

In timed games, a section labeled **Clocks** displays the remaining time for both players. This helps you keep track of how much time is left for each side to make their moves. The time is updated live as the game progresses.

Note that this section is **not visible** in **unlimited games**, where there is no time control.

#### Heading Level 2: Actions

This section contains several buttons that allow you to control or end the game. These buttons are located near the bottom of the page and are accessible by pressing `B` in Browse Mode or by tabbing.

* **Abort Game**: This button appears only at the start of the game, before any moves have been played. Pressing it will cancel the game immediately and remove it from your history. It does not require confirmation.

* **Offer Draw**: This option is available only when playing against a human opponent. It sends a draw request, and your opponent can choose to accept or decline it. If you are playing against the computer, the "Offer Draw" button will be greyed out.

* **Resign**: Pressing this button ends the game immediately and awards the win to your opponent. It is executed right away without a confirmation message.

* **Takeback**: This button appears once at least one move has been made. It allows you to undo the last move. If you're playing against the computer, the takeback is applied instantly. If you're playing against a human, a takeback request is sent, and your opponent must accept it before the move is undone.

These actions are helpful when something goes wrong, when you want to end the game respectfully, or when correcting a mistake in casual play.

#### Heading Level 2: Board

This section contains the actual **8×8 grid** of the chessboard, where the game is played. You can navigate it directly or interact with it using commands, as we will explore later.

#### Heading Level 2: Advanced Settings

This section allows you to adjust how **pieces** and **square names** are announced. Since these settings affect how you experience the board and game feedback, it’s helpful to review and configure them **before you begin playing**.

## 4.2 Understanding and Adjusting Board Settings

In the **Advanced Settings** section, you can customize how information is presented on the screen and how moves and squares are announced. These settings affect both the spoken feedback from your screen reader and the layout of the board. It’s recommended to review them before you begin playing.

Below are the key options and what they do:

### Move Notation

**Move notation** determines how chess moves are spoken and displayed — for example, in the move list, or the last move announcement.

You can choose from the following styles:

* **Anna**: Example: *knight takes filex3*
  Uses special spoken-friendly phonetics (anna for A, bella for B, caesar for c etc.) and square names like "felix3".
  Useful for players who are used to phonetic or tactile board systems.

* **NATO**: Example: *knight takes foxtrot3*
  Uses the NATO phonetic alphabet — alpha, bravo, charlie, etc.
  May be more familiar to users in military or aviation contexts.

* **Literate**: Example: *knight takes f6*
  Spoken using regular letter names and numbers. Easy to understand and natural-sounding.

* **SAN (Standard Algebraic Notation)**: Example: *Nxf3*
  Compact and traditional chess notation used in books and websites.
  N = Knight, x = capture, f3 = destination square.

* **UCI (Coordinate Notation)**: Example: *g1f3*
  Describes moves using the starting and ending square.
  More technical, often used in engine interfaces.

> 🛈 This setting affects how moves are shown in the **move list**, **last move**, and how your screen reader reads your move input from the command field or the board.

### Page Layout

This setting changes the **position of the actions section** (Abort, Resign, etc.) in relation to the chessboard.

* **Actions/Board**: The buttons appear **above** the chessboard.
* **Board/Actions**: The buttons appear **below** the chessboard.

Choose the one that feels more natural for your navigation style. Some users prefer having the controls closer to the input field or board.

### Board Settings

These settings control how **pieces and squares are announced** as you navigate the **chessboard itself** — the actual 8×8 grid. They do not affect the move list, the command field, or any other page element. They are especially important if you prefer to **move square by square** using the board instead of typing your moves.

Each option below determines **how much information you hear**, **how it's structured**, and **how your screen reader interprets the board**.

#### Piece Style

This setting controls how the piece itself is spoken when you land on a square containing a piece:

* **Letter**:
  Announces a lowercase letter representing the piece, such as `p` for pawn or `n` for knight.

* **White Uppercase Letter**:
  Same as above, but white pieces are displayed in **uppercase** (e.g., `P` for white pawn, `r` for black rook). Helps distinguish colors by case.

* **Name**:
  The piece’s full name is spoken, such as “pawn”, “rook”, or “bishop”.

* **White Uppercase Name**:
  displays the white piece name in uppercase.
  Example: `Pawn` for white, `pawn` for black.

> Example: If you move to square c2 with a white pawn:
>
> * Letter: `p`
> * White Uppercase Letter: `P`
> * Name: `pawn`
> * white uppercase Name: `Pawn`

#### • Piece Prefix Style

This determines how the **color of the piece** is announced:

* **Letter**:
  `w` for white, `b` for black.
  For example: `wP` for white pawn

* **Name**:
  Says “white” or “black” before the piece name or letter.
  For example: “white pawn”

* **None**:
  The color is **not announced at all** — only the piece is spoken.

> This setting is useful if you prefer faster navigation or already know whose turn it is or if you use upperCase to differintiate colors.

#### Show Position

This controls the **order** in which the square and the piece are spoken when you navigate the board:

* **Before**:
  The square name comes **first**, followed by the piece.
  Example: `c2: white pawn`

* **After**:
  The piece is announced **first**, followed by the square name.
  Example: `white pawn: c2`

* **None**:
  The square name is **not included** — only the piece is announced.

#### • Board Layout

This controls the **HTML structure** of the board and how it behaves with your screen reader:

* **Plain**:
  A simplified layout with no semantic structure (no table, no row/column headers).
  This layout works best in **Focus Mode** and is usually faster and more responsive when using arrow keys to navigate.

* **Table**:
  The board is presented as a real HTML **table**, with each rank and file represented by rows and columns.
  Best used with **Browse Mode** and screen readers that support **table navigation keys**, such as:

  * NVDA: `Ctrl + Alt + Arrow Keys`
  * JAWS: `Alt + Ctrl + Arrow Keys`
  * VoiceOver: `VO + Arrow Keys` within tables

> If you prefer using keyboard shortcuts to move by column or row, or want clear positional context (like “row 7, column D”), table layout is helpful. If you prioritize speed and simple key movement, the plain layout is likely better.

### 4.3 The Command Input Field

One of the most important elements of Lichess Blind Mode is the **Command Input Field** — a text box where you can type **chess moves**, **game commands**, or special **shortcuts** to interact with the game.

This field appears in the section labeled **“Input Form”** (you can reach it by pressing `e` to jump to the edit fields directly). Screen readers often announce it as: `"Your move, edit "` or `"Command input, edit box"`

To type in this field, your screen reader must be in **Focus Mode** (Forms Mode or Interaction Mode). If you're still in Browse Mode, your keystrokes will not be registered as input.

#### Entering Moves: Algebraic Notation

The command input field uses **algebraic notation**, which is the standard way of writing chess moves.

Examples:

* `e4` – move a pawn to square e4
* `Nf3` – move a knight to f3
* `O-O` – kingside castling
* `O-O-O` – queenside castling
* `exd5` – capture a piece on d5 with a pawn from the e-file
* `Qh5+` – move the queen to h5 with check

> If you're unfamiliar with algebraic notation, you can read this simple, accessible guide:
> [Understanding Algebraic Notation](https://en.wikipedia.org/wiki/Algebraic_notation_(chess))

Typing one of these notations in the command field and pressing **Enter** will execute the move on the board.

#### Using Game Commands

In addition to moves, you can type a variety of **single-letter or word-based commands** in the command field. These commands provide game information or allow you to navigate the position. Here's a full list with explanations:

* **`C`** – Read both clocks (your time and your opponent’s). Your time is announced first. You can also type the word Clock if you wish.
* **`L`** – Announce the **last move** played on the board. You can also type the word "last" Instead.
* **`P [piece]`** – List the locations of all pieces of a given type.
  Example: `P N` (capital N) announces the squares of **white knights**; `P q` (lowercase q) lists **black queens**. This means that the capital letters refer to the white pieces, and the small letters refer to the blac, ones. p for pawns, r for rooks, n for knights, b for bishops, q for queen, and k for king.
* **`S [rank/file]`** – Read all pieces in a specific **row or column**.
  Example: `S 1` reads all pieces on the first rank. `S a` reads all pieces on file A.
* **`O`** – Announce the **opponent's username and rating**.
* **`Board` or `B`** – Move focus to the chessboard.
  You can optionally specify a square, e.g., `board a1` or `b a1` to jump to square a1. The default square is `e4`. remember to leave a space between the command and the square name.
* **`Abort`** – Abort the current game. Only works before any move is made.
* **`Resign`** – Immediately resigns the game.
* **`Draw`** – Offer a draw to your opponent or accept a draw offer (only works in human games).
* **`Takeback`** – Request a takeback. Instantly accepted by the computer; requires approval from a human opponent.
* **Promotion using `=`** – To promote a pawn to something other than a queen, use `equals`.
  Example: `a8=R` promotes a pawn to a rook on a8, `b1=k` promotes to a knight.

  ⚠️ Commands must be typed exactly and followed by **Enter**. Some screen readers may not announce repeated output if the command result hasn’t changed. If you typed any incorrect command, you will get a message telling you that this is an invalid move.
  
The command input field is especially useful for players who use a **physical chessboard** to feel the position and decide their moves by touch. Once they’ve chosen a move, they can quickly type it into the field using standard algebraic notation. It’s also ideal for players who rely on **mental visualization**, sometimes called **blindfold chess**, where they track the game in their mind and enter moves directly.

For example, when you start the game and type `e4`, the move is submitted instantly, and if you're playing against the computer, it will respond almost immediately. Since it doesn't think like a human, it usually plays its reply without delay. However, if you're playing against a human opponent, you might have to wait — especially in slower time controls or as the game becomes more complex.

Lichess can announce square names and moves in different styles, such as the Anna method, which uses phonetic letters like “eva 7” instead of “e7”. These spoken formats are fully customizable in the Advanced Settings section, where you can choose how piece names, colors, and square names are announced as you navigate the board or listen to moves.

## 4.4 Navigating the Chessboard

In addition to using the command input field, you can directly interact with the **8×8 chessboard** using your screen reader and keyboard. This method allows you to **explore each square**, **select pieces**, and **make moves manually** by pressing the **Spacebar**.

1. Use arrow keys or shortcut commands to move across the board square by square.
2. When your focus is on a square containing one of your pieces, press **Space** to select it.

   * You’ll hear a confirmation sound to indicate that the piece is selected.
3. Then move to the destination square using arrows or shortcuts and press **Space** again to complete the move.
4. If you make a mistake or change your mind, you don’t need to manually cancel your selection. Simply navigate to another square and press **Space** to select a new piece — the previous selection will be **automatically cleared**.

This method is especially useful for players who like to explore the position physically and prefer **direct interaction over typing moves**.

### Board Navigation Commands

Below is a list of **keyboard shortcuts** that work while the chessboard is focused. These help you gather game information or move quickly around the board.

* **`i`** – Move focus to the **command input field**.
  Use this if you prefer to type a move instead of navigating the board.

* **`o`** – Announce the **current square** and the piece (if any) on it.
  For example: "david 4, white bishop".

* **`c`** – Announce the **piece captured** in the last move (if any).
  Useful for tracking exchanges.

* **`l`** – Read the **last move** made on the board.
  For example: "Knight to gustav 5".

* **`t`** – Announce both **clocks** — your time is always announced first.

* **`m`** – After selecting a piece, press `m` to hear all **possible legal moves** for that piece.
  The list is read out based on current game rules.

* **`Shift + m`** – After selecting a piece, press this to hear only the **possible captures** the piece can make.

### Quick Navigation Shortcuts

These shortcuts help you jump to specific types of squares or positions without using arrow keys:

* **`k, q, r, b, n, p`** – Jump to squares containing a specific type of piece:

  * `k`: king
  * `q`: queen
  * `r`: rook
  * `b`: bishop
  * `n`: knight
  * `p`: pawn
    Press the letter repeatedly to cycle through matching pieces.
    Use the **uppercase version** (e.g., `K`) to reverse the search direction.

* **`1` to `8`** – Jump directly to a **rank** (row) on the board.
  For example, pressing `2` moves you to rank 2.

* **`Shift + 1` to `Shift + 8`** – Jump to a **file** (column) from `a` to `h`.
  For example, `Shift + 3` takes you to file `c`.

* **`Shift + A` / `Shift + D`** – Step **backward or forward** through the move history.
  This lets you review past moves without leaving the board.

These commands allow for a hands-on, responsive experience, especially useful when reviewing games, planning attacks, or simply navigating comfortably.

### Practice Scenario: Playing a Simple Opening with the Board

Let’s say you're playing as **White** in a game against the computer. You’ve just created the game, and the board is focused.

Your goal is to play the common opening move **pawn to e4** using the board interface.

1. **Navigate to the pawn on e2**:

   * Use your **arrow keys** to move through the board.
   * When your screen reader announces “eva 2, white pawn” (depending on your settings), you are on the correct square.

2. **Select the pawn**:

   * Press **Spacebar**. You will hear a sound confirming the pawn is selected.

3. **Move to e4**:

   * Press the **up Arrow** twice to reach eva 4 (e4).
   * Your screen reader should say “eva 4”.

4. **Place the piece**:

   * Press **Spacebar** again. The move is made: your pawn moves from e2 to e4.

5. **Listen to the result**:

   * Lichess will announce the move and the computer’s response immediately.
     For example: “You played pawn to eva 4. Black played pawn to eva 5.”

* Press **`l`** to repeat the last move if you missed it.
* Press **`t`** to check your clock and the opponent’s time. You will usually hear nothing useful if you previously selected the unlimited time control while creating the game, as this type of game works without clocks.
* If you want to know all the legal moves for a piece before committing, select the piece and press **`m`**.
* If you want to move using the command field instead, press **`i`** to jump to the input form and type `e4`.

 ### important notes
* **Note about repeated screen reader output:**
  Depending on your screen reader settings, if the text output from Lichess is **exactly the same** as the previous message, it may **not be read aloud again**.
  For example, if you press **`L`** to hear the last move, and then press **`L`** again without any change on the board, you might not hear anything — even though the command was accepted. This applies to commands issued in the command input as well as the board.
  This can also happen during gameplay. For instance, if **White captures on d4**, and then **Black immediately does the same**, the screen reader might not announce Black's move because the **spoken output is identical** to the previous one. You will still hear a move sound effect, but no spoken feedback.
  To work around this, you can issue a different command (like `T` to hear the clocks), then press `L` again to refresh the spoken output.

* refreshing during games:
  If your opponent appears to be taking too long to move — even though their clock is ticking — it may be that the page didn’t update correctly. In such cases, press **F5** to refresh the page. After refreshing:
  If it’s your move, your screen reader will announce that it’s your turn.
  If your opponent still hasn't moved, it will say "waiting for opponent."

* leaving a game accidentally:
  if you happened to leave a game while being in the middle of playing it, you can go back to Lichess's home page, where you will find a heading called "ongoing games".
  Down arrow from there, and you will find the game you left. Just activate the join button to return to it and make your move.

 ---

## 5. Analysis

When a game concludes, the interface will change to reflect the final result — for example:

**“1–0 Checkmate • White is victorious”**

### 5.1 Post-Game Actions

The list of available actions will update and include:

* **Rematch**: Starts a new game with the same opponent using the same settings but with reversed colors.
* **New opponent**: Searches for a new opponent using the same game parameters.
* **Analysis board**: Opens a detailed review of the finished game.
  This is a **powerful tool** for reviewing your performance move-by-move.

> Note: While some parts of the analysis board are still not fully accessible, much of it is usable with a screen reader, and we will cover all accessible features in this section.

### 5.2 Analysis Board Overview

When you activate the **Analysis board**, the page title updates to include:

* The names of both players.
* The name of the **opening** used in the game (e.g., Sicilian Defense).

  > **Beginner’s tip:** A **chess opening** refers to the initial sequence of moves that shape the early stage of the game. Openings follow common patterns that help players develop their pieces and control the board. Learning openings can provide a solid foundation for the rest of the game.

The layout of the page is similar to the regular game screen, but with some new components.

### 5.3 Computer Analysis Section

Just below the command input form, you'll find:

* Checkbox: Enable local engine evaluation

  * By default, this is **unchecked**.
  * If checked, you will see the engine evaluation (e.g., `+1.3`) for the current position using **Stockfish 17.1** in your local browser.
  * **Engine evaluation**: A numerical estimate of which side is better in a given position. A **positive number** means an advantage for **White**, while a **negative number** means an advantage for **Black**. The value is typically measured in **centipawns** (1.00 = one pawn advantage).

* Engine Settings (Advanced users)

  * Allows customizing the engine behavior, such as depth and evaluation speed.
  * Most users can ignore this section unless they understand engine configurations.

* “Request Computer Analysis” Button

  * Sends your game to the Lichess servers for deeper analysis.
  * Once submitted, you’ll hear: **“Server-side analysis in progress”**.
  * After a moment, you’ll hear: **“Server-side analysis complete”**, and several new elements appear.

### 5.4 Analyzing Mistakes

Now that the game is analyzed, Lichess will provide feedback directly in the **Move List**. You'll hear things like:

> **7. Bc4 Blunder. Best move was Bd3.**
> **10. Bb4 Blunder. Best move was dxc4.**

Each move is annotated with:

* **Inaccuracy**: A move that is slightly weaker than the best.
* **Mistake**: A clearly worse move that loses an advantage.
* **Blunder**: A significantly bad move that may cost the game.

#### Average Centipawn Loss (ACPL)

Below the **Computer Analysis** heading, you'll find two level 3 headings:

* **White player: 62 Average centipawn loss**
* **Black player: 48 Average centipawn loss**

> **ACPL** measures the average difference (in hundredths of a pawn) between your moves and the engine's top suggestion. Lower is better — elite players have ACPL below 20.

Each player has a combo box listing their inaccurate or poor moves. Selecting a move jumps the board to that position.

### 5.5 PGN and FEN Downloads

Below the board, you'll find the **Downloads section** (Heading level 2):

* **PGN (Portable Game Notation)**: A widely used text format that records an entire chess game, including player names, moves, results, and optional commentary. It allows you to save, share, or replay games on any chess platform that supports PGN.

  * **Copy PGN to clipboard**: Share or save the full game with annotations.
  * **Download annotated**: Download the game including move comments and analysis.
  * **Download raw**: Download the game without analysis.

* **FEN (Forsyth-Edwards Notation)**: A concise string that represents a specific board position, including piece placement, turn to move, castling rights, en passant targets, and move counters. Useful for resuming games or analyzing particular positions.

  * **Copy FEN to clipboard**: Useful for resuming or studying a position.

### 5.6 Keyboard Shortcuts (Analysis Mode)

When focused anywhere **except the board**, the following shortcuts are available in **Focus Mode**:

* **Arrow keys**: Move forward/backward through the game moves.
* **Space**: Play the best computer move.
* **C**: Announce engine evaluation.
* **X**: Show tactical threats.
* **L**: Toggle local engine evaluation.
* **Z**: Toggle server engine analysis.

While **focused on the chess board**, several keyboard shortcuts become available that help you explore and explain positions more effectively:

* **`Shift + A / D`**:
  Moves **backward or forward** through the game's moves.
  You can use this to retrace the game one move at a time — useful for reviewing mistakes or showing how a position developed.

* **`Alt + Shift + A / D`**:
  Cycles through **variations** or **alternate lines** that were suggested by the engine during analysis.
  If a move was marked as a mistake or blunder, the engine often recommends a better line. These shortcuts allow you to explore those better paths and understand why your original move wasn’t ideal.

### 5.7 Command Input in Analysis

All the regular game commands still work, plus a few more:

* **`eval`**: Speak the engine's evaluation of the current move.
* **`best`**: Announce the top engine move suggestion relative to the current position.
* **`prev` / `next`**: Go to the previous or next move.
* **`prev line` / `next line`**: Switch between different variations or recommended lines.

> These allow you to explore alternate paths the engine suggests — especially useful after a mistake or blunder.

---

## 6. Puzzles

Lichess offers a rich collection of **chess puzzles**—short tactical problems based on real games—designed to help you sharpen your skills and recognize common patterns like forks, pins, skewers, and mates. Solving puzzles regularly can greatly improve your calculation and decision-making during actual games.

At the top of the Lichess homepage, you’ll find a **“Puzzles”** heading in the main menu. It contains several useful links:

* **Puzzles**: Launches random puzzles tailored to your current rating. These test your tactical skills and adapt in difficulty as your rating improves.
* **Puzzle Themes**: Lets you choose puzzles by theme. For example:

  * *Fork*: Find a move that attacks two pieces at once.
  * *Mate in 1*: Deliver checkmate in a single move.
  * *Discovered Attack*: Move a piece to reveal an attack from behind.
* **Puzzle Dashboard**: A personalized page that tracks your puzzle rating, accuracy, and performance trends.

When a puzzle loads, you’ll see a familiar interface similar to a normal game. Use the **command input** or **board navigation** to make your move.

If you're stuck, you have options:

* Press the **“View Solution”** button in the **Actions** section to reveal the correct answer.
* Press **`V`** in the **command input** to achieve the same.
* Once solved, use the **“Continue”** button, which is found under the actions heading, to move to the next puzzle.

In the **Settings** section of the page, there’s a **difficulty combo box** where you can choose the puzzle level, ranging from easiest to hardest, depending on how much challenge you want.

Puzzles are a fun and efficient way to build your tactical strength—especially helpful when paired with engine analysis and regular gameplay.

---

## 7. Broadcasts

One of the most exciting features of Lichess is the **Broadcasts** section, which allows users to follow **live games from top-level chess tournaments** around the world in real time. This includes world-class events like the **World Championship**, **Chess Olympiad**, **World Cup**, **Candidates Tournament**, and many more regional, national, or youth tournaments. These events cover various time controls, such as classical, rapid, blitz, and bullet formats.

Watching live games gives players the chance to study **professional-level play** as it unfolds—move by move. It's a great way to **observe different styles**, **understand high-level decision making**, and see **how grandmasters handle pressure**. With Lichess’s accessible interface, blind and visually impaired users can enjoy this experience equally.

### Accessing Broadcasts

From the **top menu**, choose **“Watch”**, then activate the **“Broadcasts”** link. This takes you to a page with all currently running and upcoming tournament broadcasts, as well as **archives of past tournaments** that can be replayed at any time.

The **“Live Broadcasts”** section is under **heading level 1**. Use **browse mode heading navigation** to reach it quickly.

Each listed tournament shows whether it is live or upcoming. When focused on a tournament name, **press the Up Arrow once** to hear how much time is left until it begins—or if it's currently in progress.

### Following a Tournament Game

When you open a tournament broadcast, the first heading will typically be **“Study Details”** (heading level 1). Here, you can use **combo boxes** to choose exactly which game to follow. These may include:

* **Group**: For example, *Open*, *Women*, *Boys*, or *Girls*, depending on the event structure.
* **Round**: The specific round of the tournament you want to explore.
* **Chapter**: The individual games or boards available for the selected group and round.

Once you make your selections in the combo boxes, the page updates to load that particular game.

### Viewing the Game

You’ll now see a **familiar interface**, similar to a regular game or analysis page:

* Use the **command input field** or **navigate the board** just like before.
* Under the **Computer Analysis** section, you can **enable engine evaluation** to see who's better and what the best moves are.
* The evaluation bar and move suggestions provide insight into how the players are performing at every stage.
* If the game is ongoing, moves will update **in real time**. If it has finished, you’ll also be able to see **inaccuracies, mistakes, and blunders**, with best move suggestions.

### Tournament Details and Results

At the **bottom of the page**, there is another **heading level 1** titled **“Tournament Details”**, which includes:

* A description of the tournament
* Notable players
* External links to official websites or results pages

Below this is a **ranking table** showing the **current standings** of all players in the event, sorted by performance. This table is fully accessible and readable with screen readers.

## 8. Studies

**Studies** on Lichess are one of the most powerful and flexible tools for learning and teaching chess. A **study** is like a multimedia notebook that can contain games, puzzles, annotations, text commentary, and variations. It’s perfect for preparing lessons, analyzing games, sharing ideas with friends or students, or simply studying your own progress.

Lichess offers a wide range of study types created by users around the world. Some studies are **public**, meaning anyone can view and learn from them, while others are **private**, shared only with specific users or study groups. You’ll find studies focused on **openings**, **endgames**, **tactical motifs**, **historical games**, and even **interactive lessons** with embedded puzzles. Some users also use studies to annotate their tournament games, run online classes, or collaborate with coaches and students. Whether you're a beginner or a master, there's a study out there tailored to your level and interests.

You can read the official Lichess blog post introducing studies here:
**[Study Chess the Lichess Way](https://lichess.org/@/lichess/blog/study-chess-the-lichess-way/V0KrLSkA)**

#### How Studies Work

on the top menu, there is a "learn" heading, below it are some learning-related tools. Arrow down through these links until you reach studies, and activate it. You will land in a page containing several studies categories,  browse them at your convenience and see what could be of interest to you.

When you open a study, the interface will look familiar—it resembles the broadcast or analysis pages:

* At the top, there are usually **combo boxes** to help you navigate:

  * **Group**: Organizes games or materials by category (e.g., openings, tactics, endgames).
  * **Round**: May be used in tournament-like studies or lesson series.
  * **Chapter**: Each chapter is an individual section of the study, like a specific game or training topic.

Just like in broadcasts, selecting the group, round, or chapter **updates the content** below automatically.

### Reading Notes and Annotations

One of the key strengths of studies is that they allow authors to add **annotations, move comments, and commentary text** alongside the game.

* All of this content appears **in the move list**, and is **fully readable with screen readers in browse mode**.
* As you navigate through the moves, you’ll hear the move itself and any text the study creator has added—such as “This was a blunder,” “Black should try c5 next,” or “Typical positional idea.”

This makes studies especially valuable for **blind players**, coaches, or learners, as all the instructional content is **accessible and clearly structured**.

---

## 9. Miscellaneous Features

Lichess is far more than just a place to play chess. It’s a massive platform with a wide range of features and tools that serve players of all levels — from casual learners to professional competitors. While we’ve focused primarily on core gameplay and Blind Mode navigation in this tutorial, it’s important to highlight some of the many other services and community functions the site offers. These tools can enrich your chess experience, help you connect with others, and support your personal growth in the game.

In the following items, we’ll briefly explore some of these features. While they may not be directly tied to Blind Mode, they are screen reader accessible and can be navigated using the same techniques we've introduced.

### 9.1. Teams on Lichess

Teams on Lichess are online chess communities where players with shared interests, nationalities, clubs, or goals come together. They allow members to participate in team tournaments, post messages, and engage in group activities.

Joining or creating a team is a great way to build community, join regular competitions, and stay connected with other players.

**To access the Teams page:**

* Go to the **top of the page**.
* Press **H** until you reach the heading **“Community.”**
* Arrow down to find the **“Teams”** link and press **Enter**.

**On the Teams page, you can:**

* **Browse existing teams**: Search by name or explore featured or popular ones.
* **Read team descriptions**: See what the team is about, whether it’s for casual play, a school club, a regional community, or a national team.
* **Join a team**: Some teams are open to everyone; others may require approval from a team leader.
* **Create your own team**: Choose a name, set a description, and decide whether it will be open or invite-only.
* **Participate in team battles**: Many teams host regular tournaments or friendly matches against other teams. These often appear under the **Tournaments** tab.

### 9.2. Arena Tournaments on Lichess

Lichess makes it easy to participate in fast-paced, competitive chess through **Arena Tournaments**, which are fully accessible with screen readers.

To access Arena Tournaments:

* From the top of the Lichess page, locate the **"Create a game"** link.
* Just **below it**, you’ll find a link called **“Arena Tournaments.”** Press **Enter** to access it.

On the Tournaments page, you can:

* **Browse active and upcoming tournaments**.
* **Join a tournament** with a single click — no extra registration needed.
* **Create your own** tournament if you are logged in.

Arena tournaments are especially dynamic because:

* Players **keep getting paired** automatically as soon as they finish a game.
* You don’t need to wait for a new round — you can play as many games as time allows within the tournament duration.
* **Scoring rewards speed** and winning streaks. For example, if you win two or more games in a row, your next win may count for double points.

Lichess also offers **Swiss tournaments**, which are typically created by team leaders and can only be joined by members of that team. Unlike Arena tournaments — where players are paired continuously and can play as many games as possible within the tournament duration — Swiss tournaments follow a **structured round-based system**, where each player plays the same number of games and rounds begin at the same time for everyone. This makes Swiss tournaments more suitable for formal and balanced competition settings. Both formats are fully accessible, but **Arena** tournaments are often more casual and fast-paced, while **Swiss** tournaments provide a more traditional tournament experience.

### 9.3. import games

Lichess provides a powerful **Import Game** feature, allowing users to paste or upload a game in **PGN (Portable Game Notation)** format to get a fully interactive replay. Once imported, you can:

* Navigate through the moves using the keyboard or board.
* Request **computer analysis** to evaluate mistakes, blunders, and best moves.
* Access a **publicly shareable link** to send the game to others.
* Read or add comments via the **game chat** area.

⚠️ **Note**: Any PGN **variations** (alternative lines) included in the file will be erased during this import. If you want to preserve them, it’s better to import the PGN into a **study**, which supports multiple variations and commentary.

You can choose to **paste the PGN** into the text box or **upload a PGN file** from your device. There’s also a checkbox to request immediate computer analysis. Keep in mind that imported games are publicly accessible unless imported through a study.

### 9.4. Chat

Lichess includes a built-in **chat feature** that allows users to communicate during games, while spectating, or when following **live tournament broadcasts**.

* During a **game**, the chat box is located **just before the game information section**. You can jump to it using the **E** key to navigate between edit fields.
* In a **broadcast**, the chat is found **at the bottom of the page**, below the board and game details.
* The **most recent messages** appear **above the chat box**, not below it.
* To send a message, **type in the chat field** and press **Enter** — your message will be posted immediately.
* **Incoming chat messages are automatically read aloud** by screen readers. This can be helpful for staying engaged, but may also become distracting — especially during broadcasts when you want to focus on analyzing moves rather than reading comments.
* To manage this, press **H** to reach the **“Chat” heading** (level 1). Just below it, there’s a **“Live board”** tab. Pressing this will **hide the chat widget entirely**.
* You can return to the chat at any time by pressing the **“Live chat”** tab.

If you prefer to **disable chat altogether**, you can do so from your **Privacy settings** under **User Preferences**.

Here’s a refined and structured version of the paragraph:

---

### 9.5. Your Account

One of the great features of Lichess is that it automatically tracks all your activity on the site — from games and puzzles to studies and forum posts.

To access your profile:

* Click on your **username** from the main page (usually found at the end of the top menu, below the challenges and notifications), then press **Enter** on **"Profile"**.

Your profile page provides a wealth of information, including:

* Your **ratings** for each chess variant you've played.
* Your **puzzle rating** and progress.
* The number of **studies** you've created or contributed to.
* **Forum posts** and community activity.
* Detailed **game history** for each variant:

  * You can see your **best victories**, **toughest defeats**, and the **average rating** of your opponents.
  * Filter your games by time control, opponent strength, color, and result.

The best way to discover everything your profile has to offer is simply to explore. Don’t worry — you can’t break anything by looking around.

### 9.6. Many more

Here’s a list of other useful and interesting Lichess features that you may explore. While not all are essential for blind users, many are fully accessible and can enhance your experience on the platform:

* **Customizing your Profile**:
  You can add a bio, change your username (once), upload an avatar, manage preferences, and adjust website behavior and so on.

* **Following Other Players**:
  You can follow friends, top players, and streamers. Their activity will appear in your dashboard and you can spectate their games easily.

* **Explore Games**:
  View recent games by other users, browse top games of the day, or watch master games. Use the search and filter tools to focus on specific openings, players, or time controls.

* **Lichess Blog**:
  The [official Lichess blog](https://lichess.org/blog) covers feature updates, community stories, tournament news, and several announcements. It’s a great way to stay informed.

* **Opening Explorer**:
  Study how chess openings are played across millions of games by masters and users. Filter by rating, time control, or era.

* **Learn Section**:
  Includes Chess Basics, Practice, Coordinates Training, and Learn From Your Mistakes — ideal for improving your skills. Some are partially accessible and being improved.

* **Practice Against the Computer**:
  Set up custom board positions and play against Stockfish at any strength.

* **Leaderboard & Rankings**:
  See top players in bullet, blitz, rapid, classical, puzzles, and more. Filter by country or time frame.

* **Lichess TV**:
  Automatically spectate top-rated games in real time.

---

## 10. Contributions

Lichess is open-source and constantly evolving thanks to the contributions and feedback from its users — including screen reader users like you.

If you found this guide helpful and want to contribute to improving it or reporting issues related to accessibility, here are some ways to get involved:

* **Suggest Edits or Improvements to This Guide**: If you notice any mistakes or think certain areas could be better explained, feel free to suggest edits or share feedback. Contributions from other blind or visually impaired users are especially valuable in making this guide better for everyone.

* **Report Bugs or Accessibility Issues**:

  * Visit the **[Lichess GitHub repository](https://github.com/lichess-org/lila/issues)**.
  * You can create a new issue explaining the problem you're facing.
  * Be clear and detailed — include what screen reader you're using, the browser, and steps to reproduce the issue.

* **Request Features or Join Accessibility Discussions**:

  * Participate in the **[Lichess Feedback Forum](https://lichess.org/forum/Lichess-feedback)**.
  * Share your experience, request improvements, or join ongoing conversations about accessibility and user interface behavior.

* **Stay Informed and Connected**:

  * Follow updates on **Lichess blogs** or **social media** to stay aware of new features that may impact accessibility.
  * Engage with the wider Lichess community — developers are very receptive and supportive of improving accessibility for everyone.

Your feedback helps not just yourself but many others in the blind and visually impaired chess community.

**This guide was prepared by Ekramy Medad. For feedback, collaboration, or contributions, you can connect with me on [GitHub](https://github.com/ikrami1).**
