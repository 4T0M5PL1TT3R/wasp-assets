# wasp-assets
Data files for WaspLib.
These are semi-automated cache dumps

## Want to fork this repo?
First you need a GitHub account.

Then you need to click the fork button:
<img width="604" height="202" alt="image" src="https://github.com/user-attachments/assets/c06d0626-07be-421d-97d2-9f7a10d31e7d" />

On the page that opens keep everything as is and click "Create Fork"

## Enabling GitHub actions

This is so the repon semi-automated updater runs every 6h, it will check for updates and if anything changed a Pull Request will be created.

On your forked repo page go to the settings tab:
<img width="947" height="232" alt="image" src="https://github.com/user-attachments/assets/5fb530e5-6886-4be5-93bc-a9cac9a8a346" />

Then go to the Actions general page:
<img width="294" height="636" alt="image" src="https://github.com/user-attachments/assets/12ccf080-cab3-488f-8960-848cfcdbfd06" />

Ensure the bottom part looks like this with with "Read and Write permissions enabled" and "Allow GitHub Actions to create and approve pull requests" and click save:
<img width="980" height="367" alt="image" src="https://github.com/user-attachments/assets/b7cc1144-1eb5-4dce-962f-d9648d307c4d" />

And you are done, you should have it checking for updates every 6 hours and creating a Pull Request if there's anything that changed.
