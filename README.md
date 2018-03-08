# Prose Test

A static website built with care, leveraging jade, sass, harpjs, github, prose.io and aws.

## Connecting

Visit [prose.io](prose.io) and connect your github account. You will need to need to give prose.io access to your account so be sure to have your credentials (username and password) handy.

## Updating

If you haven't yet... visit [prose.io](prose.io) and connect your github account.

**Once you are connect follow the following steps to publish your new content.**

1. Choose the project you would like to add content to from the list of available repositories and navigate to the directory you want your new content to live in.

2. Begin by clicking on the "New File" button, you will be taken to the prose.io editor. Once there you can create your new folder and file by simply typing in the **\[new-page-name]/index.md**. ![Screen Shot 2018-03-08 at 8.34.05 AM.png]({{site.baseurl}}/new-page-name/Screen Shot 2018-03-08 at 8.34.05 AM.png)

3. Now just type away using the prose.io editor tools and save your new page.

4. Next lets tell the system a little more about our new page. We are going to do this by creating a _data.json file in in that same folder we just created. navigate to that folder and click the "New File" button again. This time lets name it _data.json. Uses the following as the base for content of that file. once you are done save it.
```json
{
  "index": {
    "slug": "This is the folder you created this file in.",
    "title": "The new page title",
    "description": "The description of the new page... no line breaks or funny charachters please.",
    "category": "The category for new Talking Points",
    "keywords": "These will be used for seo and potentially sorting."
  }
}
```

5. Now lets go take a look at what we just built on our [staging](https://test-prose-staging.herokuapp.com/). If there are any issues or typos adjust them using the steps above.

6. Once we are confifdent in out ne content we can deploy it to production by visiting aws.blah blah blah. and finding our instance and clicking the promote button.

**All Set!**

