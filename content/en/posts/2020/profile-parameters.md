---
title: "Configuring Your Profile Section"
date: 2023-12-16
tags: ["hugo","configuration"]
image : "/img/posts/2025/9.jpg"
Description  : "Below is a list of configurable parameters in the Lightbi theme, along with descriptions to help you customize your site effectively."
draft: 
---

Your site's homepage profile section is controlled by a handful of parameters in your config file. Below is a breakdown of each one.

###### Profile  Parameters

1. **`profileWelcomeHeading`**  
    - **Type**: String
    - **Description**: The main greeting displayed at the top of your profile section. This is typically your name or a short introductory phrase.

    ```toml
    profileWelcomeHeading = "Hi I'm Lightbi"
    ```

2. **`profileWelcomeSubHeading`**  

- **Type**: String
- **Description**: A subheading shown directly below the welcome heading. Use this to set the tone for your site — a tagline, mission statement, or brief description of what visitors can expect.

```toml
profileWelcomeSubHeading = "Welcome to my digital garden!"
```

3. **`profileShortbio`**  

    - **Type**: String
    - **Description**: A short biography or introduction displayed in the profile section. This gives visitors context about who you are and what kind of content they'll find on your site.

    ```toml
    profileShortbio = "I'm passionate about the web platform and love creating for the web. Here, you'll find a mix of long essays, quick notes, and personal reflections on what I've learned throughout my journey."
    ```

4. **`profileExploreText`**  

    - **Type**: String
    - **Description**: A short call-to-action prompting new visitors to explore the site further, usually paired with a button or link.

    ```toml
    profileExploreText = "If you're new here, feel free to explore the website by clicking the below button."
    ```

5. **`profilePhoto`**  

    - **Type**: String (file path)
    - **Description**: The path to your profile photo, relative to your `static` directory. This image is displayed alongside your welcome heading and bio.

    ```toml
    profilePhoto = "img/profile/home-profile-pic.jpg"
    ```


Together, these five parameters power the profile section most visitors see first — a quick snapshot of who you are before they dive into your content.


