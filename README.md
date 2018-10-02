# Dark Mode Switcher

## How to make the Dark Mode Switcher

1. Launch the Automator
2. Choose a type as Application for your documents
3. Find Actions, 'Run AppleScript'
4. Type the AppleScript
5. Save the action in the Application folder

*Optional Steps*:

6. *Add your own icon*
7. *Keep in dock*

### Launch the Automator

![dm_0](./img/dm_0.png)

### Choose a type for your documents

Choose Application type

![dm_1](./img/dm_01.png)



### Find Actions

Find Actions 'Run AppleScript'

![dm_02](./img/dm_02.png)



### Type the script like below

![dm_03](./img/dm_03.png)

AppleScript Code:

```
tell application "System Events"
	tell appearance preferences
		set dark mode to not dark mode
	end tell
end tell
```

### Add your own Application Icon

![dm_04](./img/dm_04.png)

### Keep in Dock

![dm_05](./img/dm_05.png)

---



## Run the Dark Switcher

![Dark-Mode-Switcher](./img/Dark-Mode-Switcher.gif)

