
# Section 1.5 — Terminal Conventions

Welcome to your next BMS-BOOST interactive Terminal exercise!

In this lesson, you will practice several conventions that make working in the terminal easier and help you avoid common mistakes.

## Exercise 1 — Capitalization Matters

Command names in the terminal are generally case-sensitive. This means that uppercase and lowercase letters are treated differently. 

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
Notice that the terminal displays the current working directory again, just as it did when you first entered `pwd`.

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


## Exercise 3 — Using Tab Completion

The **Tab** key can help you finish typing commands and file or directory names.

Instead of typing an entire command, you can enter the first few letters and press Tab.

**Step 1:** In the terminal below, type `whoa` but do not press Return.

**Step 2:** Press the **Tab** key once.

**What happened?**

If the shell recognizes a unique matching command, it should complete `whoa` to `whoami`.

**Step 3:** Press Return to execute the completed command.

**Expected output:**

```text
sandbox
```

**What does this mean?**

The shell recognized the beginning of a command and completed the remaining characters for you.

**Try it yourself:** Type `pw`, press Tab, and observe whether the shell completes the command to `pwd`.

If the shell finds multiple possible matches, it may not complete the command automatically.

**Key takeaway:** Tab completion can save time and reduce typing mistakes.


### Check Your Understanding

1. What is the purpose of the Tab key in the terminal?
2. You type `whoa` and press Tab. The shell completes the command to `whoami`. Has the command executed?
3. What should you do if pressing Tab does not complete your command?

<details>
<summary>Reveal answers</summary>

1. Tab completion helps finish command, file, or directory names, reducing typing and spelling mistakes.
2. No. The command has been completed but has not executed. Press Return to execute it.
3. Check your spelling or type additional characters. The shell may have multiple possible matches or may not recognize what you entered.

</details>


## Exercise 4 — Stopping a Running Command

Sometimes a command takes longer than expected to finish. Other commands may continue running until you stop them.

You can usually interrupt a running command by pressing **Control+C**.

Let's practice using a command called `sleep`.

The `sleep` command pauses for a specified number of seconds without displaying any output.

**Step 1:** In the terminal below, type `sleep 30` and press Return.

**What happened?**

The terminal appears to be doing nothing. This is expected! The `sleep` command is waiting for 30 seconds.

Notice that the command prompt has not returned.

**Step 2:** Before the 30 seconds have elapsed, press **Control+C**.

**What happened?**

The running command should stop, and the terminal prompt should reappear.

You may also see `^C` displayed in the terminal.

**What does this mean?**

Pressing Control+C sends an interrupt signal to the running command. Many commands respond by stopping and returning control to the shell.

**Try it yourself:** Run `sleep 20` and interrupt it using Control+C before it finishes.

**Key takeaway:** Control+C is a useful way to interrupt a running command. On a Mac, use the Control key, not the Command key.

### Check Your Understanding

1. What does the `sleep 30` command do?
2. Why does the terminal prompt temporarily disappear while `sleep` is running?
3. Which keyboard shortcut can you use to interrupt a running command?

<details>
<summary>Reveal answers</summary>

1. It pauses for 30 seconds without displaying output.
2. The shell is waiting for the running command to finish or be interrupted.
3. Press **Control+C** to send an interrupt signal. Many commands respond by stopping.

</details>


## Exercise 5 — Clearing the Terminal Display

As you work in the terminal, commands and their output accumulate on the screen.

Sometimes it is helpful to clear the display so you can focus on your next task.

The `clear` command clears the visible terminal display without deleting files or erasing your command history.

**Step 1:** In the terminal below, type `whoami` and press Return.

**Step 2:** Type `pwd` and press Return.

**Step 3:** Type `echo "Welcome to BOOST."` and press Return.

Notice how the commands and their output appear in the terminal.

**Step 4:** Type `clear` and press Return.

**What happened?**

The previous commands and their output should disappear from the visible terminal display.

A new command prompt should appear, ready for your next command.

**What does this mean?**

The `clear` command clears the terminal display. It does not delete files, remove directories, or erase your command history.

**Try it yourself:** Press the Up arrow key to recall a previously entered command.

Notice that your command history is still available even though you cleared the display.

**Key takeaway:** Use `clear` when you want a clean terminal display without affecting your files or command history.

### Check Your Understanding

1. What does the `clear` command do?
2. Does `clear` delete files or directories?
3. After running `clear`, can you still recall previous commands using the Up arrow key?

<details>
<summary>Reveal answers</summary>

1. It clears the visible terminal display.
2. No. It does not delete files or directories.
3. Yes. Command history remains available after clearing the display.

</details>





