<p align="center">
<img src=https://raw.githubusercontent.com/Reach-Industries/Frontend-Test-2022/main/RI-FrontendTest-Github.png?raw=true/>
</p>

![](https://img.shields.io/github/stars/Reach-Industries/Frontend-Test-2022.svg) ![](https://img.shields.io/github/forks/Reach-Industries/Frontend-Test-2022.svg) ![](https://img.shields.io/github/tag/Reach-Industries/Frontend-Test-2022.svg) ![](https://img.shields.io/github/release/Reach-Industries/Frontend-Test-2022.svg) ![](https://img.shields.io/github/issues/Reach-Industries/Frontend-Test-2022.svg)

The Task
=============
A single page application that makes two REST api calls to retrieve two data files, and then display the associated data in an appropriate way.

**First call**<br />
https://mockapi.lumi.systems/getdevices <br />
Using the userId = 100, and orgId = lumi<br />
Retrieve an array of deviceIds <br />

**Second call**<br />
https://mockapi.lumi.systems/getdevicedata <br />
Using the userId = 100, orgId = lumi and deviceId = LumiWifi-dVr<br />
Retrieve the device resources files <br />

**Retrieved Data**<br />
There will be two files to retrieve and display, A Video file and a corresponding JSON data file. <br />
The JSON file contains a <br />
- Bounding box of the sample area labelled "RoI"<br />
- Frame Array which matches each frame in the video file. 
- Frame data is contains the average Red, Green, Blue pixel values and a histogram difference value.<br />

<p align="center">
<img src=https://raw.githubusercontent.com/Reach-Industries/Frontend-Test-2022/main/example_json.png?raw=true/>
</p>

**Displaying Data**<br />
The video file must be displayed in a video player that allows the user to stop and start the video, and must display a frame track bar. <br />
The corresponding frame data must be displayed on the page for each frame of the video. 

Below is only an example of the possible way to display the data and is not a requirement.<br />
<p align="center">
<img src=https://raw.githubusercontent.com/Reach-Industries/Frontend-Test-2022/main/Frontend-Test-Example.jpg?raw=true/>
</p>

Requirements
=============
Submissions must be built using
- Javascript
- Typescript
- React

All sourcecode must be submitted via GitHub, with the repo shared on the career portal questionaire, or submitted as a reply to the career application response email.

Must make the two required queries, display and play the video file, and display the associated frame data.

Bonus Points
=============
**Live Site**<br />
A self-hosted live site accessible for the reviewing team. 

**Styling**<br />
Althought not a requirement, sites with html, css styling, and suitable layouts will score higher than those with none.

**Colour Palette**<br />
<p align="center">
<img src=https://raw.githubusercontent.com/Reach-Industries/Frontend-Test-2022/main/Colour-Palette.png?raw=true/>
</p>

**Data Display**<br />
Display the complete history of the sample colour in a single view in a way that corresponds to the video trackbar.

**Login Modal**<br />
Allow the user to dynamically add the User and Organisation information.

**Device Select**<br />
Allow the User to select a device from a list returned from the api endpoint.

FAQ
=============
**-How Much should I do?**<br />
  How long is a piece of string? It is totally up to you how much you complete, but the reviewing team will look at quality and quantity when ranking submissions.

**-How Many Times Can I submit?**<br />
  Once, please just update your GitHub repo, depending on when the submission is reviewed the updated repo might not be seen.

**-Can I use other technologies other than those listed in the Requirements**<br />
  Yes as additional technologies, but due to the nature of the available roles we would like to see the use of JavaScript, TypeScript and React.

Contact Details
=============

careers@reach.industries

Disclaimer
=============
**Minimum Submission Requirements**<br />
  For a submission to guarantee an automatic interview all stages of the task must be complete. Reviewer discretion will be applied. 

**Polite Recruiter Note** <br />
  We currently do not wish to work with any external recruiters or agencies, please do not contact us at this stage as it will jeopardise any opportunity of working together in the future.
