jweb-hands-landmarker

A Max/MSP patch that maps MediaPipe hand tracking data to real-time sound synthesis and audio effects.
Installation

    Make sure you have Max 9 or later installed.

    This project assumes you have a working MediaPipe Hands data stream integrated via jweb, node.script, or similar methods (not included here).

    Download or clone this repository.

    Open jweb-hands-landmarker.maxpat in Max.

Usage

    Start your camera-based hand tracking system (e.g., jweb with MediaPipe Hands).

    Open the patch and activate audio by clicking the audio toggle (ezdac~).

    Move your left hand in front of the camera.

        Joint coordinates are routed through subpatches.

        Hand movement affects pitch, gain, and modulation in real time.

    Use on-screen dials to adjust:

        Pitch transposition (Transp)

        Glide (smoothing time)

        Quality (for pitch shifting)

Note: All joint landmarks (e.g., index_finger_tip, pinky_finger_dip) are unpacked and can be routed individually for customized control.
History

    13.05 – Initial version with basic hand tracking data routing

    03.06 – Implemented pitch shifting and gain control based on landmark positions

    X.06 – Final UI adjustments, smoothing with line~, and scale calibration for joint-based synthesis

Links

    MediaPipe Hands documentation

    Max/MSP

    Git LFS (for handling large files)

    Markdown Cheat Sheet

Project Development

To get started:

    Create a GitHub account

    Download and install GitHub Desktop

    Read this guide and keep the Markdown Cheat Sheet handy

Then follow this process (inspired by this source):

    Fork this template to your own GitHub account

    (You can set the repo to Private if preferred. Just add your evaluator as a collaborator so they can access it.)

    Clone the repo using GitHub Desktop to work locally

    Commit and push regularly as you work. The last pushed version before the deadline is the one that will be evaluated.

Required Elements

    A complete README file — including title, description, usage, history, and useful links.
    You can also include images, animated gifs, or links to audio/video demos.

    The statement-of-originality.yml filled out.
    Anything not listed there is assumed to be your own work.

    The project itself. All code must be present and runnable according to your instructions.
    If your project uses large assets (audio/video/etc), use Git LFS or link to a downloadable resource in the install instructions.
