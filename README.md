Tekken 8 Drills

Setting up drills repeatedly in Tekken 8 can be tedious, particularly since the game does not automatically save drills between sessions. This challenge is even greater when precise timing, such as consistent dashes, is required.

To streamline this, I've leveraged @whyd's XInput Injector to transform these drills into an easily executable Jupyter Notebook. This means once you've set up everything initially, running drills becomes as simple as launching a notebook.
Credits

A special thanks to the creators who made this project possible:

    WHYD for the XInput Injector
    Speedkicks and Phidx for designing these effective drills
[        Speedkicks Twitter
](https://twitter.com/Speedkicks)        

[Phidx Twitter
](https://twitter.com/PhiDXGames)
Getting Started

    Install Python:
        Visit the official Python website and follow the instructions to download and install Python. Ensure you add Python to your system path.
        https://www.python.org/downloads/
    Install Jupyter Lab:
        Open PowerShell and run the following command:

        pip install jupyterlab

    Download and Set Up the XInput Injector:
        Download the repository from this [link](https://gitlab.com/loic.petit/xinput-inject).
        Extract the repository to a convenient location on your computer.

    Download the Jack Drill:
        Download the Jack Drill notebook from this repository and place it in the same folder where you extracted the XInput Injector.

    Launch Jupyter Lab:
        Navigate to the folder where you extracted the XInput Injector.
        Right-click within the folder and select 'Open terminal here'.
        Type jupyter lab and press Enter. This will open Jupyter Lab in your default web browser.

    Open the Drill Notebook:
        In the Jupyter Lab interface, navigate to and open the drill notebook located on the left-hand side.

Running Drills

Currently, the repository features the Jack drill as the main example. Here’s how to use it:

    In Tekken 8, go to the practice mode and start the recording.
    In the Jupyter Notebook, press Shift + Enter to begin executing the first drill. Watch as Jack performs the actions on screen.
    After the first drill, save it to slot 2 and press Shift + Enter again to proceed with the next drill.
    Continue this process until all four slots are filled.

Ending Your Session

    Ensure to run the 'Lab Stop' cell at the end of your recording to properly close the lab.

Customizing Your Drills

This setup is adaptable for any drill or scenario you wish to practice. If you're interested in creating your own drills:

    Refer to the XInput Injector documentation on GitLab.
    Use the provided drills as templates. Basic coding experience will be helpful.

Future Updates

Plans are underway to expand the drill repository and enable community contributions. Stay tuned for updates, and soon you’ll be able to upload your own drills.

You’re now all set to run the drills directly from the notebook!
