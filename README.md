# EDA Youtube Project

## 📚 Table of Contents

- [🧾 Quick Summary](#-quick-summary)
- [🎯 Project Objective](#-project-objective)
- [📊 Who is this analysis for?](#-who-is-this-analysis-for)
- [🔍 My Personal Motivation](#-my-personal-motivation)
- [🌐 Project Scope & Context](#-project-scope--context)
- [📈 What exactly did I do?](#-what-exactly-did-i-do)
- [🧩 Variables from the YouTube API](#-variables-from-the-youtube-api)


### 🧾 Quick Summary:

- ✅ Exploratory project with real YouTube data from different countries 🌍  
- 🧠 Focused on understanding patterns in trending videos  
- 🧹 Extracted, cleaned, and transformed the data using Python  
- 📊 Analyzed key metrics: views, likes, duration, tags, and more  
- 📁 Final clean dataset in `.csv` [here](https://drive.google.com/uc?id=1v2onHqf7lmhaNaPQsc1m_ervym7EDLMS)  
- 🧑‍💻 Full code available on my [GitHub](https://github.com/camila-guerra)

---

### 🎯 Project Objective

I've always been fascinated by what can be discovered through large volumes of data.  
The **YouTube API** offers a goldmine of information ready to explore: trends, audience behavior, video impact... all in real time!

💡 **What's the point of this project?**

I wanted to explore what makes a video trend on YouTube — by looking at real data from different countries 🌎.

The idea isn’t to draw big conclusions, since it’s just a few weeks of data, but to spot initial patterns and practice data cleaning, analysis and visualization skills using Python.

It’s a mix of curiosity + hands-on learning 🧠📊

---

### 📊 Who is this analysis for?

Even if you think this is just for YouTubers...  🚫 Wrong!

This data is also super useful for:
- 📈 **Companies and brands** wanting to advertise on YouTube  
- 🧠 **Market analysts** interested in consumer behavior patterns  
- 🧑‍💻 **Curious people like me** who want to understand what content hits hardest and why  

---

### 🔍 My Personal Motivation

🎨 **I love “Trivia facts”!**

I've always trusted statistics and data. For some reason, my brain gets captivated by patterns and constantly wants to find them.

💡🧠 I enjoy looking for hidden connections and understanding the “why” behind what we see. I'm very curious about people's behavior, as well as how statistics are collected and measured.

---

### 🌐 Project Scope & Context

📅 **Analyzed Dates:**

* From **March 11 to April 8, 2025**

📍 **Frequency:** 

* Once a week

🌎 **Regions:** 

Argentina, Bolivia, Brazil, Chile, Colombia, Costa Rica, Dominican Republic, Ecuador, El Salvador, Uruguay, Guatemala, Honduras, Mexico, Nicaragua, Panama, Paraguay, Peru, Puerto Rico, Venezuela, Canada, United States.

> ⚠️ **Disclaimer:**
> *I know a longer period would allow for stronger conclusions, but for practical purposes, this range helps identify clear initial patterns.*

---

### 📈 What exactly did I do?

✅ **Analysis with Python:**  
- I used `Pandas`, `Seaborn`, and `Matplotlib` to analyze trending YouTube videos 📊  
- Worked with data from several countries: 🇦🇷 🇲🇽 🇺🇸 🇨🇦 🇩🇪 🇬🇧 🇮🇳

✅ **Data Cleaning:**  
- Checked and handled null and empty values 🚫  
- Converted columns like `tags` and `publish_time` into proper formats 🔄  
- Filtered out invalid categories and consolidated the dataset 🧹

✅ **Processing and Visualizations:**  
- Mapped categories by `category_id`  
- Grouped by country and category to compare trends 🌍  
- Analyzed key metrics like:  
  - **Views** 👀  
  - **Likes** ❤️  
  - **Comments** 💬  
  - **Duration** ⏱️  
  - **Number of Tags** 🏷️  
  - **Publishing Time** ⏰  

✅ **Key Findings:**  
- Some categories dominate depending on the country 🏆  
- More duration or tags ≠ more views ❌  
- Publishing time varies in impact depending on the region 🕒

### Want to know the rest? Stick around and see if you can spot them!

> 📑👇 A PDF with more detailed conclusions is available at the end.

---

### 🧩 Variables from the YouTube API

  - 🎥 **video_id**: Unique video identifier.  
  - 📝 **title**: Video title.  
  - 📖 **description**: Video description.  
  - 📅 **published_at**: Date and time the video was published.  
  - 👤 **channel_id**: Unique identifier of the channel that uploaded the video.  
  - 📺 **channel_title**: Name of the channel.  
  - 🗂️ **category_id**: ID of the category the video belongs to.  
  - 🏷️ **tags**: Tags associated with the video.  
  - ⏱️ **duration**: Video duration in ISO 8601 format.  
  - 🖥️ **definition**: Video definition quality.  
  - 🔤 **caption**: Indicates whether the video has subtitles.  
  - 👀 **view_count**: Number of views.  
  - 👍 **like_count**: Number of likes.  
  - 💬 **comment_count**: Number of comments.  
  - 🧒 **made_for_kids**: Indicates if the video is marked as kid-friendly.

> 📘 **More info:**  
Check out the [official YouTube API documentation](https://developers.google.com/youtube/v3/docs/videos?hl=en) for technical details.


---
---

