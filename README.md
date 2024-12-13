<!---
Copyright 2024 Colten Wade Parker. All rights reserved.

Licensed under the MIT License;
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    https://opensource.org/licenses/MIT

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
-->

<p align="center">
  <img alt="asset" src="https://cdn.vectorstock.com/i/500p/16/54/checkerboard-black-and-white-background-vector-33401654.jpg" width="5000" height="10" style="max-width: 100%;">
  <br/>
  <br/>
</p>

<p align="center">
  <img alt="Images To Roblox Parts" src="https://i.postimg.cc/mDfm6ydS/Untitled86-20241130213821.png" width="422" height="422" style="max-width: 100%;">
  <br/>
  <br/>
</p>

<h6 align="center">
    ~ Made with Lua, Python, Flask, and Vercel! ~
</h6>

<h1 align="center">
    <a href="https://github.com/coltenthefirst/image-to-roblox">
        <img alt="License Info" src="https://img.shields.io/badge/License-MIT-blue.svg">
    </a>
    <a href="https://github.com/coltenthefirst/image-to-roblox/releases">
        <img alt="Newest Release" src="https://img.shields.io/github/release/coltenthefirst/image-to-roblox.svg">
    </a>
    </a>
        <a href="https://vercel.com/">
        <img alt="Vercel Deploy Status" src="https://deploy-badge.vercel.app/?url=https%3A%2F%2Fvercel.com%2Fcoltenthefirsts-projects%2Fimage-to-roblox&logo=Vercel&name=Vercel+%28image-to-roblox%29">
    </a>
</h1>

<p align="center">
  <img alt="asset" src="https://cdn.vectorstock.com/i/500p/16/54/checkerboard-black-and-white-background-vector-33401654.jpg" width="5000" height="10" style="max-width: 100%;">
  <br/>
  <br/>
</p>

<h1 align="center">
    Images To Roblox Parts (Model-3 Released)
</h1>

<br>

<p align="center">
  <img alt="asset" src="https://cdn.vectorstock.com/i/500p/16/54/checkerboard-black-and-white-background-vector-33401654.jpg" width="5000" height="10" style="max-width: 100%;">
  <br/>
  <br/>
</p>

#### If you use Model-2. Please read this: [fix](https://github.com/coltenthefirst/image-to-roblox/issues/5)

## Introduction

This repository contains the backend source code for the **Image To Parts** Roblox Game. This tool allows users to convert image URLs into parts within Roblox. Users are free to use the files provided in this repository for their own purposes.

## How It Works
Here’s a overview of the process:
1. Input an image URL and select a quality setting (such as mid, high, low, extra low).
2. The image URL and selected quality are sent to **Vercel**.
3. Vercel downloads the image and runs a Python script based on your selection.
4. A Lua script is generated and sent back to Roblox, where it is processed into parts that resemble the pixels of your image.

## Cloning Vercel and Github

#### Make sure you make a github account and go to https://vercel.com and make a vercel account by connecting your github account to vercel.
#### Click This:
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fcoltenthefirst%2Fimage-to-roblox&env=FLASK_APP&envValue=server.py&env=FLASK_ENV&envValue=development&project-name=image-to-roblox&repository-name=image-to-roblox)

### Tutorial Video: [Vercel Setup Tutorial YouTube Link](https://youtu.be/RcwPO3fshEU)

#

##### Set "FLASK_APP" as "server.py"
##### Set "FLASK_ENV" as "development"
##### Once its deployed. Go to the settings tab of your vercel project, click on General and click on Project Settings.
#### Overwrite the Build Command as "flask run --host=0.0.0.0 --port=5000"
#### Overwrite the Install Command as "pip install -r requirements.txt"
##### You can go back to the Project page and click on the thumbnail preview that says "Not Found", don't worry, this is normal. Once you are on the site, click on the spacing where the url ends and type "/send_image". It should look like "https://your-vercel-project-name.vercel.app/send_image".
##### Model-2 and below: Go to your copyed Roblox game and open serverscriptservice and open the script "ImageRequestHandler". After that, replace the line "local url = "https://image-to-roblox.vercel.app/send_image"" as your url, like "local url = "https://your-vercel-project-name.vercel.app/send_image"".
##### Model-3 and higher: Go to your copyed Roblox game and open serverscriptservice and open the module script "ServerlessWebsites". After that, replace the line "Urls.Image = "https://image-to-roblox.vercel.app/send_image"" as your url, like "Urls.Image = "https://your-vercel-project-name.vercel.app/send_image"". You can also replace "Urls.Gif = "https://image-to-roblox.vercel.app/send_gif"" as "Urls.Gif = "https://your-vercel-project-name.vercel.app/send_gif"" (model-3 is unreleased)
### Now you're done! You can visit your github profile and you can find the cloned repo, you can edit this repo and do whatever you want with it.

#

## To-Do List

<h6 style="text-align: right;">
    ~ EXPECT THESE TO CHANGE!!! ~
</h6>

### Current Tasks (IN ORDER) - Model-3 Planned

- [ ] Placeholder (Other) - Unknown

### Completed Tasks

- [x] Release (Github/Model-1)
- [x] Frame By Frame Animation Player (Model-2)
- [x] Faster Image Gen Speed (Model-2)
- [x] Enhanced image data privacy (Github)
- [x] Improved support for black and white images and single-color images (Github)
- [x] Add a frame-by-frame animation player (Model-2)
- [x] Add a delete button for parts (Model-2)
- [x] Fix Error 500 (Github/Model-2)
- [x] Resolve issue with the first pixel not generating (Model-2)
- [x] Updated README.md (Github) - released
- [x] Automatic Frame By Frame Animation Player (Github/Model-3)
- [x] Making A Logo (Github)
- [x] Color Filters (Model-3)
- [x] More Customizable Image Options (Model-3)
- [x] Fix The Frame By Frame Animation Player Bug
- [x] Fix Other Bugs (Github/Model-3)
- [x] Updated README.md #2 (Github)
- [x] Boring Website (Other)

### Completed Tasks Since Model-3 Released

- [ ] Placeholder (Other) - Unknown

## Videos
| Info                            | Video |
|------------------------------------|--------|
| Model-1 Release: |[Model-1 YouTube Link](https://www.youtube.com/watch?v=oFm_znA53r8)|
| Model-2 Release: |[Model-2 YouTube Link](https://www.youtube.com/watch?v=6pRmz4_hoDo)|
| Vercel Setup Tutorial: |[Vercel Setup Tutorial YouTube Link](https://youtu.be/RcwPO3fshEU)|
| Model-3 Release Video Soon: ||

## Game Link
| Name                            | Link |
|------------------------------------|--------|
| Create Your Dreams: |[Create Your Dreams Roblox Link](https://www.roblox.com/games/128560311364952/Create-Your-Dreams)|


You can download the place files here:

| Model / Update                            | Download |
|------------------------------------|--------|
| Update 1/Model-1: |[Google Drive Link](https://drive.google.com/file/d/1YdDMn-is_UD_VkbfgQKzQ3mzjJb5QZHY/view?usp=sharing)|
| Update 2/Model-2: |[Google Drive Link](https://drive.google.com/file/d/1GUnPJWO0sX8VsMysFi1eTUbYXyJKcshk/view?usp=sharing)|


## Uploading Custom Images
For obtaining direct image urls, I recommended to use [Postimages.org](https://postimages.org/) to obtain a direct link. Other services can be used as long as they provide a direct link.

## Tested Image Services
### ✅ Recommended (Works)
#### Free, No Account Needed
- **[Postimages.org](https://postimages.org/)** — *Highly recommended*. Supports GIF uploads.
- **[imgbb.com](https://imgbb.com/)** — *Highly recommended*. Supports GIF uploads.
- [imghippo.com](https://imghippo.com/) — Supports GIF uploads.
- [imgbox.com](https://imgbox.com/) — Supports GIF uploads.
- [lunapic.com](https://www7.lunapic.com/editor/?action=quick-upload) — Supports GIF uploads.
- [imagevenue.com](https://www.imagevenue.com/) — Supports GIF uploads.
- [pictr.com](https://pictr.com/upload) — Supports GIF uploads.
- [imagebam.com](https://www.imagebam.com/) — Supports GIF uploads.
- [imgbly.com](https://imgbly.com/) — Supports GIF uploads.
- [picsur.org](https://picsur.org/upload) — Supports GIF uploads.
- [pixhost.to](https://pixhost.to/) — Supports GIF uploads.

#### Free, But Limited Functionality
- **[snipboard.io](https://snipboard.io/)** — Does *not* support GIF uploads.

### ❌ Not Recommended (Does Not Work)

- [i.imgur.com](https://i.imgur.com/) — Direct Links Are Broken
- [prnt.sc](https://prnt.sc/) — Direct Links Are Broken
- [freeimage.host](https://freeimage.host/) — Direct Links Are Broken
- [dropbox.com](https://www.dropbox.com/) — Direct Links Are Broken
- [imghostr.com](https://imghostr.com/) — Direct Links Are Broken



## FAQ

**Q: Does this have a NSFW filter? (All Models and Github)**
######
**A:** No, this does NOT have a nsfw filter.

##### -

**Q: What happened to the NSFW filter version? (Other)**
######
**A:** The NSFW filter wasn't very good at detecting NSFW images or NSFW words in images. It was very buggy and was very messy to take care of. The apis also stopped working. Sorry for shutting it down but I couldn't keep working on it anymore. You can always make a fanmade NSFW Filter. Maybe if this project gets known more, then I will make another NSFW filter. Thank you.

##### -

**Q: Do my uploaded images get logged? (All Models and Github)**
######
**A:** Uploaded images are temporary logged, they cannot be downloaded, viewed, or anything, unless its in Roblox.

##### -

**Q: Will I get banned for using exploit images? (Other)**
######
**A:** I said before that you won't be banned, but you can be banned. Please be careful when using this in your games.

##### -

**Q: Why is the send gif function split into different files? (Github)**
######
**A:** Since this whole project is free, I can't edit the timeout time. So I spit the send gif function into different files, so it wouldn't timeout when uploading the frames. 

##### -

**Q: Why is the animation player not working? (Model-2)**
######
**A:** Please read this: [fix](https://github.com/coltenthefirst/image-to-roblox/issues/5)

##### -

**Q: Why is the animation player not working? (Model-3)**
######
**A:** Sometimes the api key can get rate limited and for it to work again, you would have to wait a hour. Or you can make another api key, delete the old one, and use the new one. I don't have a fix for this yet but, I could make it send to another image hoster, or I could make a script that checks if the api key works or not, and if it doesn't than what it would do is use another api key. I will fix this in Model-3.5.

##### -

**Q: How can I help on this project? (Other)**
######
**A:** You can star this project or, dm me on discord if you want to help another way: "unknowingly_exists"

##### -

## License
This project is licensed under the MIT License. You are free to use, modify, and distribute the files in this repository, as long as you include the original license. For more details, see the [LICENSE](LICENSE) file.

## Contributing
Contributions are welcome. If you have suggestions or improvements, please open an issue or submit a pull request.
