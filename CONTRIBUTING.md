# Contributing

If you participated in the #10DayWebBuild and would like to show off your project, you can follow these steps to create your own community member page:

1. Fork and clone this repository.
2. Create a new branch `community/YOURUSERNAME`, where YOURUSERNAME is your github username.
3. In the directory `_community`, copy the `TEMPLATE.md` file and fill out the information you wish to share. You can also reference `EXAMPLE.md` for an example of how your file may look.
4. Create a folder in assets/images/community/YOURNAME. YOURNAME is the same as the name you used for the name field in your `_community/YOURNAME.md` file. For example, if in your file in `_community` has the field `name: john_doe`, then the folder name will be `assets/images/community/john_doe`.
5. Add your profile picture to the folder you just created. This picture must have the same name as the `image:` field in your `_community/YOURNAME.md`. For example, if you have `image: myprofile.jpg`, then your picture will be located at `assets/images/community/YOURNAME/myprofile.jpg`.
6. Add all of your projects' image and video files to this folder. This pictures and videos must have the same name as the `image:` or `video:` field listed for your projects in your `_community/YOURNAME.md` . For example, if you have
```yaml
projects:
  - name: Finance Tracker
    image: finance_tracker_demo.gif
    url: https://johndoe.com/finance_tracker
    repo_url: https://github.com/johndoe/finance_tracker
    description: "A tracker that tracks your finances."

  - name: YouTube Clone
    video: youtube_demo.mp4
    url: https://johndoe.com/youtube_clone
    repo_url: https://github.com/johndoe/youtube_clone
    description: "A clone of youtube"
```
then your files will be located at `assets/images/community/YOURNAME/finance_tracker_demo.gif` and `assets/images/community/YOURNAME/youtube_demo.mp4`.
7. Verify that all of your information is correct. Using the example from EXAMPLE.md:
```yaml
---
layout: author

name: john_doe
display_name: John Doe
image: john_doe_picture.png # image located in assets/images/community/john_doe/john_doe_picture.png
about: "I am a Software Engineer that likes to build projects. I have a deep interest in AI."

socials:
  github: https://www.github.com/johndoe
  twitter: https://www.twitter.com/johndoe

projects:
  - name: Finance Tracker
    image: finance_tracker_demo.gif
    url: https://johndoe.com/finance_tracker
    repo_url: https://github.com/johndoe/finance_tracker
    description: "A tracker that tracks your finances."

  - name: YouTube Clone
    video: youtube_demo.mp4
    url: https://johndoe.com/youtube_clone
    repo_url: https://github.com/johndoe/youtube_clone
    description: "A clone of youtube"
---
```
you would have the following files:
```
assets/images/community/john_doe/john_doe_picture.png
assets/images/community/john_doe/finance_tracker_demo.gif
assets/images/community/john_doe/youtube_demo.mp4
```
8. Commit your changes and push them to your forked repository.
9. Create a PR to push these changes to the official repository.
10. Once we review and approve your PR, your page will be available on the official community page.