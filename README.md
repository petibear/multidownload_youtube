About
=====

Just a super simple powershell script to execute [youtube-dl](https://github.com/ytdl-org/youtube-dl) iteratively with.

Links to the youtube videos to be downloaded are to be placed in [links.txt](./links.txt).

Latest version of [youtube-dl](https://github.com/ytdl-org/youtube-dl) needs to be installed with its executable in your `PATH`.

Execution policy might need to be amended in a powershell ran by administrator:

```powershell
Set-ExecutionPolicy -ExecutionPolicy Unrestricted
```