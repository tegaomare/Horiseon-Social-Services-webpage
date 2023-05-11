# Horiseon Social Solution Services, Inc.

<!-- ![Horiseon Logo](./assets/images/logo.PNG) -->

<img src="./assets/images/logo.PNG" alt="Horiseon Logo" width=40% height=40%>

## About This Webpage
- - - -
This webpage is the homepage of Horiseon Social Services, Inc. Horiseon is a company that provides services regarding `Social Media Marketing`, `Search Engine Optimization`, and `Online Reputation Management`

## Sourcecode Problems
- - - -

While working with this company, upon reviewing their sourcecode we were left with errors within the HTML code. Our criteria to fix this problem is as followed:

* **View the source code to find HTML elements** - To make sure the webpage's source exists with HTML elements
* **Review & Revise HTML structure** - This is to make sure the structure is followed logically
* **Review & Revise image alt attributes** - Makes sure images are correctly identifiable in the code
* **Correct header content & add title** - The header content in the code needs to be in sequential order and a title for the page must be added

### Finding The Errors

Upon reviewing the code we did find `HTML elements`. However, the structure was incorrect and the `image attributes` showed up missing as show below:

```
    <div class="benefits">
        <div class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" />
            <p>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </p>
        </div>
```

Further reviewing the code, we also found the `header` section which was incorrectly ordered and missing a unique descriptive title as show below:

```
<head>
    <meta charset="UTF-8" />
    <link rel="stylesheet" href="./assets/css/style.css">
    <title>website</title>
</head>
```

### Approaching the problems

* **Replacing placeholder `div`(s) to add correct element information**
    * We added elements such as `figure` for images & images with captions
    * Added the `section` elements to correctly group the code
    * Added `alt` attribute for easy identification of the image
    * Replaced `<p></p>` with `<figcaption></figcaption>` because this is a caption which describes the image

    ```
        <section class="benefits">
        <figure class="benefit-lead">
            <h3>Lead Generation</h3>
            <img src="./assets/images/lead-generation.png" alt="placeholder stock image" />
            <figcaption>
                Inbound strategies for lead generation require less work for your business, bringing customers directly to your website.
            </figcaption>
        </figure>
    ```

* **Reviewing & Revising Header element**
    * We corrected the order of the header by placing `<title>website</title>` before we link to a stylesheet
    * Replaced placeholder title and added a new descriptive title: `Horiseon Social Solution Services, Inc.

    ```
    <head>
        <meta charset="UTF-8" />
        <title>Horiseon Social Solution Services, Inc.</title>
        <link rel="stylesheet" href="./assets/css/style.css">
    </head>
    ```

## Conclusion
- - - -

After reviewing our criteria and making the neccessary changes, we have now relaunched the site which is available to view at: https://kankanrr.github.io/hw1-code-refactor/