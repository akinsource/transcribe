# Transcribe Web App - By Team Dragon Revenge 

## Overview

[Transcribe](http://dragonrevenge.hng.fun) is a web-based online Speech-To-Text transcription tool that help users transcribe audio files to plain text.

A useful application of this web app would be in the transcription of call center call recordings to text. 


## Tools used in building Transcribe

- Design: [Figma](https://figma.com)
- Frontend: [ORACLE JET Framework](http://www.oracle.com/technetwork/developer-tools/jet/overview/index.html)
- Backend: Node.JS
- APIs:  [Google Cloud Speech-To-Text](https://cloud.google.com/speech-to-text/) and [Amazon Transcribe](https://aws.amazon.com/transcribe/)


## How to use the app

To transcribe a file, click on the “Upload Mp3” button at the top right of the page and select an audio file (mp3, wav, mpeg, x-flac, flac) from your device to upload.  A mini notification will show up on both Amazon Transcribe and Google Cloud Speech-To-Text tabs indicating that the transcription process has begun. 

Google Cloud Speech-To-Text will automatically display the transcribed text when the transcription has been completed.

For Amazon Transcribe however, a transcription job is instead started. You would have to keep clicking on the 'Check Transcription Status' button on the Amazon Transcribe tab to check if transcription has completed or is still in progress. If it has completed, the application will output the result of the transcription job.


## Browser Compatibility

Works perfectly on Chrome (web and mobile) and also on Firefox. 


======================================================================


# Project Details 

### Assets

> Figma design: https://www.figma.com/file/FGwn7vaO97o67zZed2uUFBPS/Transcribe-App
 > <br>
> Oracle JET Getting Started: http://www.oracle.com/webfolder/technetwork/jet/globalGetStarted.html
 > <br>
> Knockout.js: http://learn.knockoutjs.com/#/?tutorial=intro

### Team Info

There are 3 sub-teams in this project.

| Team name              | Team lead (slack username) |
| ---------------------- | -------------------------- |
| Repository Maintainers | @Jeremiah                  |
| Frontend               | @Syfon                     |
| API/Backend            | @Chibuokem                 |


### Contribution instructions

1.  <strong>Do not commit to the master branch.</strong> Create a branch with a meaningful name, make your changes in it, commit and send a pull request. Your team lead will ensure that there are no merge conflicts and your code does not break anything before requesting a maintainer to merge your pull request.
2.  Each sub-team lead should create tasks as Github issues on this repository. Sub-team members can then request to be assigned to those issues. The format for a issue is '[SUBTEAMNAME]: [Issue description]'. Example: 'Frontend: The upload button does not match what is in the Figma design.'


### Running the project locally

1.  Ensure you have OJET installed. To do so, run `npm install -g @oracle/ojet-cli`.
2.  I cloned this repository locally to `C:\Users\Mbah Clinton\Documents\OJET\` so in the commandline I will run `cd C:\Users\Mbah Clinton\Documents\OJET\transcribe\frontend`.
3.  Run `npm install`. If there are any errors, retry with the commandline running as an Administrator.
4.  To run the application, run `ojet serve`.
5.  The application should now be visible at http://localhost:8000/
