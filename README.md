# Guilty Gear -Strive- x SAMMI

A Bridge Extension for [SAMMI](https://sammi.solutions). Take interactions in game and turn them into stream gimmicks!

## Extension Function

This extension allows you to receive data from [TheLettuceClub's GGST Live Content Mod](https://github.com/TheLettuceClub/StriveSAMMI-Release) in the form of Extension Triggers inside SAMMI. A collection of example buttons have been provided with some experimental functionality to get you started.

![image](https://github.com/user-attachments/assets/de66568f-f7e5-49b4-aeb9-7d291b21f3bf)

## Quick Start Guide

Step 1: Download [SAMMI](https://sammi.solutions).

Step 2: Follow the various [SAMMI Onboarding Tutorials](https://sammi.solutions/docs/getting-started/step-by-step).

Step 3: Install Guilty Gear -Strive- x SAMMI as a [SAMMI Bridge](https://sammi.solutions/docs/bridge) Extension.

Step 4: Boot up Guilty Gear -Strive- while SAMMI and SAMMI Bridge are open to automatically connect.

Step 5: Make use of the various Extension Triggers generated by Strive to drive stream gimmicks!

Step 6 (Optional): Copy the text found in the Example Deck text file to your clipboard, then import it to Sammi via the Paste Deck command. 

## Using the Mod

### Accessing Events via Extension Triggers

The following Extension Triggers are available for use. Add them to buttons via a button's Trigger menu. They all contain extremely relevant data within that can be accessed via the `Trigger Pull Data` command.

![image](https://github.com/user-attachments/assets/4170585a-6fca-4659-afc2-78e4a1679569)
![image](https://github.com/user-attachments/assets/51d28c37-d6f0-429a-b853-0d7c5aa765a9)

| Extension Trigger | Description |
| --- | --- |
| `ggst_stateUpdate`| Occurs once a frame. Contains all sorts of cool gamestate data. |
| `ggst_hitEvent` | Occurs on Hit or Block. Contains relevant data. |
| `ggst_roundStartEvent` | Triggers on Round Start. |
| `ggst_roundEndEvent` | Triggers on Round End. |

### Example of Detecting Really Big Counterhits.
This is in the Commands screen of a button set up with the `ggst_hitEvent` Extension Trigger. The ggst_hitEvent trigger sends along it's own data object that you access with `Trigger Pull Data`.

![image](https://github.com/user-attachments/assets/40435221-85ed-4672-823e-7291b9b2435a)

## More Information

Check out the documentation for [TheLettuceClub's Mod](https://github.com/TheLettuceClub/StriveSAMMI-Release) for more information.
