# MyFrenchLearningBlog_Backend

> Link to **MyFrenchLearningBlog** Angular Project _(Frontend)_: [Click Here](https://github.com/kjeshang/my-french-learning-blog)

## Software Packages

Below is a list of software packages used for the **MyFrenchLearningBlog** _Frontend_:
* Tailwind CSS
* DaisyUI
* Angular Material
* Ngx-Markdown

## Backend Structure

* _**Images Folder**_: Images that are used in "Header", "Footer", "About" and "App" Components.
* _**About.md**_: General description about me, my background, and professional work history. In addition, share reasons for learning french along with resources that I have used/currently using, which includes resources related to the blog posts that are a part of this website.
* _**data.json**_: Containing the blog posts that would be imported to the frontend project.

|Image Name|Local Image|External Image|
|--|--|--|
|purpose_logo|[Repo Link](Images/purpose_image.jpg)|[URL](https://media.istockphoto.com/id/1455207009/vector/francais-megaphone-with-language-doodle-bubble.jpg?s=612x612&w=0&k=20&c=TQ_lDap11NUWFQEzVcau0wbNonceSEw6vguJm67UZ0o=)|

### Blog Section

Structure Type = Unstructured

|_Key_ Name|_Value_ Description|Notes|
|--|--|--|
|Name|[Text]|Blog Post Name|
|Level|A1, A2, B1, B2|Language Benchmark Level|
|Link|[Text]|Link of Blog Post Markdown File|
|Reference|[Text]|Where I got the idea for the blog post (e.g., online learning course exercise, project, website activity, etc.)|
|Date|[Text]|Date Blog Post was published|

The blog posts data is saved in a `data.json` file that would be read into the frontend project from this repository. Despite blog posts being segmented by level in this repository, the posts would not segmented in the `data.json` file for the purpose of sequential-seamless import to the frontend.