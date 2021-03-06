---
layout: default
title: Text Chat
categories: beginner sidebar
published: true
---

## Chatting

<img src="/images/textchatbox.jpg" align="right" vspace="40" hspace="40" />

  Sending a basic chat message is easy: just type your message into the chat input area and press "Enter". Be advised that any player assigned a "Character" (from the Journal tab) can choose via drop-down to talk as either themselves (their registered login name) or as their assigned character.

## Rolling

  Rolling dice in Roll20 is easy. Just type the <code>/roll</code> command into the text chat box, followed by a formula. In most cases, the formula is the same as the one that's printed in your game's instructions. For example, you might know that to roll an attack roll you need to roll a "D20 plus your attack modifier". In Roll20, you would just type <code>/roll 1d20+5</code>. Notice that you need to put the 1 in front of the d20 even if you're only rolling one dice. If you hit and you need to roll 3d6+2 damage, you would just type <code>/roll 3d6+2</code>. Finally, you can also string multiple rolls together. If you have an attack that does two types of damage, you might do <code>/roll 2d6+5 + 1d8</code>.

  <div class='diceroller'>/roll 1d20+5</div>

  So, the overall format for a dice roll is <code>/roll NdX+m</code> where N is the number of dice to roll, X is the number of sides of the dice, and m is the (optional) modifier, which can also be negative.

  After the roll is performed, you'll see the results of the roll in the text chat area. Notice that for each group of dice that were rolled, there will be a group of numbers in parentheses, representing the result of each individual dice that was rolled. You'll also see the total of all the dice values plus modifiers to the right of the equals sign.
  
  Be sure to check out the [Dice Rolling Reference](/dice-rolling-reference) if you need to use more advanced dice mechancis.

## Whispers

  To whisper, simply type <code>/w</code> and the name (either player or character) you wish to engage via whisper.  Do note that there is a tab-autocomplete function for names to speed this process.
  
  To whisper directly to the GM, type <code>/w gm</code>. You can also perform a roll that only you and the GM can see, with <code>/gmroll 1d20+5</code>.

## Emotes

  To emote, type <code>/em</code> and whatever action you want stated.  Be advised that you will emote by whatever you are currently speaking as (player or charater).
  
## Chat Archives


  The chat window will keep a running history of everything entered. This history will persist between sessions, and is always available. You can also access a complete archive by scrolling to the top of your chat log, and clicking <code>View all chat entries for this campaign >></code>
  This will load the chat history in a new window.