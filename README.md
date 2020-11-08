# NetSurf browser and GNOME localisation(zh_CN)



## Table of Contents

- [Background](#background)
- [Introduction](#introduction)
- [Contributing](#contributing)

  

## Background

This project comes from the topic provided by AOSC researchers. At present, there are a considerable number of Linux and other open source or free software (F/OSS) users in China. However, in the process of using, it is not difficult for users to find that the quality of simplified Chinese translation and localization of various software is uneven, and there are many errors and omissions. For Example, Netsurf is a lightweight cross platform web browser. It supports HTML5 and CSS standards, provides a small, fast and complete web browsing solution, and supports a series of UNIX platforms such as RISC OS. As a well-known Web browser, netsurf has no simplified Chinese translation at all. Therefore, in order to improve user experience in China, this project will realize the translation of NetSurf based on GNU/LINUX programming environment.



## Introduction

**The file directory is as follows**

```
├── READEME.md
├── NetSurf-translation
├── ──── 0000-cover-letter.patch  
├── ──── 0001-resources-add-Chinese-Simplified-translations.patch       
├── ──── 0002-Makefile-add-Chinese-Simplified-translation-target.patch   
├── GNOME-translation
├── ──── aisleriot.master.zh_CN.po   
├── ──── cheese.master.zh_CN.po 
├── ──── devhelp.master.zh_CN.po
├── ──── ………………*.po  
├── ──── tracker-miners.master.zh_CN.po
```

 ***Notice:***

  1. README.md is an instructional document.
  3. There're 3 patch file under NetSurf-translation directory. This set of patches introduces full Chinese (Simplified, China; zh_CN) localisation for the NetSurf browser. The 0001.patch contains the actual translation content, while the 0002.patch contains necessary build script modifications to make this localisation work with NetSurf (details enclosed)
    3. There're many .po files under GNOME-translation directory, we've improved translation for GNOME on the basis of other translators. You can use POedit or any other text editors to view and improve it.



## Contributing

UI and resource localisation was done by Weiyi Xu and were proofread by
Mingcong Bai and Zixing Liu from the Anthon Open Source Community
(https://aosc.io/).