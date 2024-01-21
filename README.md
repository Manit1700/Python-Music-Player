# Music Player

This is a simple music player application built using Python and Tkinter.

## Features
- Add and play MP3 songs
- Delete songs from the playlist
- Save and load the playlist
- Control playback (play, pause, stop, next, previous)
- Set the volume
- Display album cover art

## Installation
1. Clone the repository
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

**Important: Please replace the paths in the code with the paths to your music and image files. For example, replace `/Users/manit/Documents2/musicplayer-main/music/` with the path to your music folder and `/Users/manit/Documents2/musicplayer-main/img/` with the path to your image folder.**

# Screenshots
## System Default Apperance
![System default color](https://github.com/Manit1700/Python-Music-Player/assets/133211146/c5fb14b7-5425-45aa-9bcf-602db71bcd94)
![Auto dark mode](https://github.com/Manit1700/Python-Music-Player/assets/133211146/1f2f3395-9ef6-4292-a7ae-fc147feaea69)
The app has the feature to set the appearance to the system color. This is done using the customtkinter.set_appearance_mode('system') function. This feature allows the app to blend in with the system's color scheme, giving it a more native look and feel.

## Add Song Menu Bar
![Add song menu bar](https://github.com/Manit1700/Python-Music-Player/assets/133211146/618c1a5c-d6e0-4fd3-949d-85f06ffde235)
Add song/songs to the playlist using the "Add Songs" menu and "Add one song to playlist" or "Add many song to playlist" in the menu.

## Remove Song Menu Bar
![Remove song menu bar](https://github.com/Manit1700/Python-Music-Player/assets/133211146/0a824401-e681-487a-842f-b496008a3fbd)
Remove song/songs from the playlist using the "Remove Song" menu and "Delete one song to playlist" or "Delete many song to playlist" in the menu.

### Note: The feature will be in the window itself when using the windows OS.
![Loading song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/0f8ea2be-643d-4063-9323-ce0770527e20)

## Playing, Forward, Back, Pause, and Stop Song
![Playing the song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/c2bac500-913c-44e8-b241-0f05710c3900)
![Forward song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/0ba921c5-9601-4745-a95d-cb3142b9e6fe)
![Back song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/8958306c-bf3d-4cc3-b1ce-b495ff084aa6)
![Pause:Unpause Song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/01fc8c76-ec40-4fdf-8d67-24602f5cbb5f)
### Note: The song will be paused and pressed the button and will be played where last paused when button is clicked again.
![Stop song](https://github.com/Manit1700/Python-Music-Player/assets/133211146/0bbc2ec2-8495-413f-a341-2b1110b4a869)

## Skip Song to any length and volume
![Skipping the song to any length](https://github.com/Manit1700/Python-Music-Player/assets/133211146/b5c4c7eb-4ba1-47ee-b4bd-b6fd40b63710)
Control playback and volume using the on-screen buttons and sliders.

## Autoplay
![Autoplay](https://github.com/Manit1700/Python-Music-Player/assets/133211146/085c25b6-1151-4e51-a6c9-69a9f0acacb0)
Autoplay switch will automatically play next song when one song is finished. If the song is last in playlist then it will play next first song of playlist.

## Save Playlist
![Saving Playlist](https://github.com/Manit1700/Python-Music-Player/assets/133211146/346155c5-0f51-43cb-9fcc-3552515679c8)
Once the playlist is saved and the app is closed, when the app is loaded again the song will be in the playlist.

## Delete and Unsave song
![Pressing Shift+Esc](https://github.com/Manit1700/Python-Music-Player/assets/133211146/99a50569-b47e-489c-a801-637dff91f8c5)
The song can be deleted and unsaved at same time using the Shift+ESC shortcut. It is only possible if the save switch is ON.
