# Frontend Mentor - Social links profile solution

I am here to argue that what you did is full of errors and warnings. I am also answering questions you may have or questions you should have in your mind.

Improving oneself is important. This is for you.

## Table of contents

Do you know that GitHub offers a native table of contents?

## The challenge

Users should be able to

- see hover and **focus** states for all interactive elements on the page; and
- view the website on their mobile device, whether in portrait or landscape mode; and
- zoom up to 200% without any horizontal scrollbar in full-screen mode.

## What I can learn if I am new

This project looks simple. But it is not as simple as you may think. I am not making this complicated. I am showing you what you may miss, which can be a lot.

### Getting your head straight

I bet that you have never heard that will teach you the most optimal order for the child elements inside the `head` element. Beginners take things for granted, but they do not know the reasons.

For this project, this is the right order:

```html
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Frontend Mentor | Social links profile</title>
<link rel="stylesheet" href="/style.css" />
```

Why is that order the best?

1. Your browser needs to know how to render the page immediately. Otherwise, the browser will re-render the page, which will delay the page from showing up.
1. The title is needed to show something to users immediately. Even if the page is still blank, at least your users know that they are connected to the website. Otherwise, on a heavy page, the users will only see the URL on their browser's tab, which can be a sign that they will fail to connect to the page.
1. The stylesheet is needed as soon as the title shows up to style your website.

> [!TIP]
> For more information on this, watch [Harry Roberts - Get Your "head" Straight - YouTube](https://www.youtube.com/watch?v=MHyAOZ45vnU).

### Understanding the landmark elements

HTML is about marking your content so that browsers can render it properly for your users. Landmark elements tell browsers what this content will be about.

- The `main` element marks all content inside it as the main content of the page. The content inside it is usually different from one page to another page.
- The `footer` element is an optional element here. But you need to know that it is usually used for secondary navigation links. If you take a look at the very bottom of the Frontend Mentor, that is the common content inside it: links, copyright statement, and logo.

### Writing alternative text

We all know that the `img` element will be used to show Jessica's photo. But most people are not aware of it. How do I know about that? They write, "A photo of Jessica Randall" or "A picture of Jessica Randall."

Including the word "photo," "image," or "picture" shows me that you use a semantic HTML element, which is the `img` element, but you do not seem to believe it.

I bet you know what you should do, right? Don't include any term related to the word "image" in 99% of cases.

### Using responsive units

Responsive units are not `px` units. Although they are scalable when your users use the browser's built-in zoom-in and zoom-out feature, they do not respect other methods. Users can change the size of a webpage through

- the browser's settings;
- the browser's extension;
- device settings;
- installed apps; and
- much more.

Users can change the size through a combination of those ways.

To keep this simple, use the `rem` unit most of the time and avoid using the `px` unit in general.

## Links

- Solution URL: https://www.frontendmentor.io/solutions/responsive-social-links-profile-without-media-queries-NTfC7ltXOk
- Live Site URL: https://officialjessica.netlify.app/

## Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- Mobile-first workflow

## License

This project is for the use of anyone anywhere in most parts of the world at no cost and with almost no restrictions whatsoever, except the Inter font family and the Frontend Mentor assets. You may copy it, give it away or re-use it under the terms of the [Unlicense](./COPYING).
