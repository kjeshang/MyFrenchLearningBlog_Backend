# MyFrenchLearningBlog_Backend

To see live version of My French Learning Blog... [***Click Here***](https://kunal-french-blog.netlify.app/)

> Link to **MyFrenchLearningBlog** Angular Project _(Frontend)_: [Click Here](https://github.com/kjeshang/my-french-learning-blog-updated)

## Software Packages

Below is a list of software packages used for the **MyFrenchLearningBlog** _Frontend_:
* Tailwind CSS
* Signal Store
* Luxon
* Plotly
* Lodash
* Ngx-Markdown

## Backend Structure

The data in the following files that would be read into the frontend project from this repository.

### _**data.json**_: Contains the blog posts data as well as links to the actual blog posts.

|_Key_ Name|_Value_ Description|Notes|
|--|--|--|
|ID|[Number]||
|Name|[Text]|Blog Post Name|
|Level|A1, A2, B1, B2|Language Benchmark Level|
|Reference|[Text]|Where I got the idea for the blog post (e.g., online learning course exercise, project, website activity, etc.)|
|Date|[Text]|Date Blog Post was published|
|Post|[Text]|Link of Blog Post Markdown File|

### _**certifications.json**_: Contains french certifications earned and links to the actual certificates.


|_Key_ Name|_Values_|Description|
|--|--|--|
|Busuu|Name [Text], Link [Text]|Name of Certification, Link to Certificate|
|Udemy|Name [Text], Link [Text]|Name of Certification, Link to Certificate|

### _**career_data.json**_: Containing Canadian work experience data, such as job title, company, location, etc.

|_Key_ Name|_Value_ Description|Notes|
|--|--|--|
|Date|[Text]|Time Period of Employment|
|Position|[Text]|Job Title|
|Company|[Text]|Name of Company|
|Location|[Text]|Company Address|


