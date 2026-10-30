
# Section 1.5 — Terminal Conventions

Welcome to your next BMS-BOOST interactive Terminal exercise!

In this lesson, you will practice several conventions that make working in the terminal easier and help you avoid common mistakes.

## Exercise 1 — Capitalization Matters

Terminal commands are generally case-sensitive. This means that uppercase and lowercase letters are treated differently.

You previously learned that `whoami` displays your current username.

**Step 1:** In the terminal below, type `whoami` and press Return.

**Expected output:**

```text
sandbox
```

**Step 2:** Now type `WhoAmI` and press Return.

**What happened?**

The terminal should report that the command was not found.

**Why?**

The shell treats `whoami` and `WhoAmI` as different command names. Although they contain the same letters, their capitalization is different.

**Try it yourself:** Type `whoami` again, using all lowercase letters. Confirm that the command works.

**Key takeaway:** Pay attention to capitalization when entering terminal commands.


### Check Your Understanding

You enter `WhoAmI` in the terminal and receive a
`command not found` error.

What is the most likely reason, and how would you
correct it?

<details>
<summary>Reveal answer</summary>

The command was entered with incorrect capitalization.

The shell treats `WhoAmI` and `whoami` as different
command names.

Enter `whoami` using all lowercase letters.

</details>


## Exercise 2 — Using Command History

The terminal remembers commands you have entered during your session.

You can use the **Up (↑)** and **Down (↓)** arrow keys to navigate through previously entered commands.

This is useful when you want to repeat a command without typing it again.

**Step 1:** In the terminal below, type `whoami` and press Return.

**Step 2:** Type `pwd` and press Return.

**Step 3:** Press the **Up (↑)** arrow key once.

**What happened?**

The command `pwd` should reappear at the terminal prompt.

Notice that the command has not executed yet.

**Step 4:** Press the **Up (↑)** arrow key again.

The command `whoami` should now appear.

**Step 5:** Press the **Down (↓)** arrow key once.

You should see `pwd` again.

**Step 6:** Press Return to execute the recalled command.

**What does this mean?**

The arrow keys allow you to navigate through commands you previously entered. A recalled command can be executed by pressing Return.

**Try it yourself:** Use the Up arrow key to recall `whoami`, then press Return to execute it.

**Key takeaway:** Command history saves time and reduces typing errors when repeating commands.


### Check Your Understanding

You entered a long command in the terminal and want to run it again without retyping it.

1. Which key would you press to retrieve the previous command?
2. Does pressing that key automatically execute the command?
3. What must you press to execute the recalled command?

<details>
<summary>Reveal answers</summary>

1. Press the **Up (↑)** arrow key.
2. No. The command reappears at the prompt but does not execute automatically.
3. Press **Return** to execute the recalled command.

</details>

