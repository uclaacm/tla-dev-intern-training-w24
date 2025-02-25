# Designing with Figma: Day 1 <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [What is Figma?](#what-is-figma)
- [Planning](#planning)
  - [Storytelling and flow](#storytelling-and-flow)
  - [Research and mood boards](#research-and-mood-boards)
  - [Color](#color)
  - [Style guides](#style-guides)
  - [Layouts](#layouts)
    - [A note on responsive design](#a-note-on-responsive-design)
- [Creating a wireframe](#creating-a-wireframe)
  - [Alignment](#alignment)
- [What makes good design?](#what-makes-good-design)
  - [Readable body text](#readable-body-text)
  - [White space](#white-space)
- [Basic prototyping](#basic-prototyping)
  - [But first, components](#but-first-components)
  - [Making connections](#making-connections)
  - [Content organization](#content-organization)
  - [Nice work!](#nice-work)
- [Sources and further reading](#sources-and-further-reading)
  - [A note on keeping up](#a-note-on-keeping-up)
  - [Keyboard shortcuts](#keyboard-shortcuts)

## What is Figma?

Figma is widely regarded as the one of the best free(mium) cloud-based platforms for web and graphic design. It is mainly used for prototyping, but I use it for simple graphic designs (like posters and stickers) as well.

Many people compare Figma to the Adobe Creative Suite. The good news is that 90% of keyboard shortcuts are the same between the two platforms. So, if you've used Adobe products before, you're in luck.

At the present, complex graphic design is still best left to programs such as Adobe Illustrator. This is because Figma doesn't yet have the capability for complex shape manipulation (Mesh, Proportion) or variable stroke width, among many other advanced features. Overall, I'd say Figma serves the bottom 70% of graphic design needs.

Throughout this tutorial, I will be referring to different toolbars. I don't know what they're actually called, but this is what I call them. For reference, I've put images of them here.

Menu bar:

![A bar containing icons for mouse, frame, shape, pen, text, pan, and comment](images/menu.png)

Layers panel:

![A panel containing groups of art layers](images/layers.png)

Options panel:

![A panel containing fields for X and Y coordinates, alignment, ](images/options.png)

## Planning

You might already have a very clear idea of what you want your design to be, or you might not. My hope is that these next few tips will be helpful, regardless of where you are in the planning process.

### Storytelling and flow

Think back to when you were in English class in high school, wondering why you were learning how to write a five-paragraph essay. That question gets answered today.

Design is visual storytelling. The process of creating a successful design should be analogous to writing a successful essay: your user will be introduced to your product, interact with it, and should come away feeling like they have had a coherent experience.

When you wrote five-paragraph essays, you were probably told to always "tie your evidence back to your thesis". When we design, we should also make sure that we always tie our designs back to these two questions:

* What is our product?
* What is the takeaway? (or, what do we want our audience to gain from our product that they hadn't had before?)
* What is the story? (or, what angle are we taking? How are we "packaging" our product to consumers? How do we separate ourselves from similar organizations or products?)

For a learning lab such as the Buffer Buffet, the answers to the above questions would be:

1. An interactive educational game
1. The importance of preventing buffer overflow
1. A restaurant or "buffet" as an analogy to computers

We can use the answers to these questions to guide construction of mood boards, style guides, and layouts, which we will cover next.

### Research and mood boards

It's good to see what's already in the field. A product is much easier to use if it follows the "unspoken rules" of similar products in the same field&mdash;often because the rules are based on years of refinement. (This was covered in last week's workshop with Rucha, so I won't go into it too much.)

Of course, there's a balance to strike here between outright plagiarism and radical creativity, but you get my point.

Hopefully, you already know what audience you are serving. Is it American elementary-school students? Healthcare workers in China? Language learners worldwide? Try looking at some designs from organizations or companies that serve a similar audience.

![The Khan Academy website front page](images/khan-academy.png)

For example, sites for kids often include bright colors and cute characters. Business and organization sites will include Terms & Conditions and a Privacy Policy in the footer, login/logout in the top right, and contact information in either the header or the footer.

You can take screenshots of colors, logos, fonts, photos, and websites that you want to refer to and paste them directly into Figma.

Some people don't like using mood boards, though, and just refer to outside resources as needed. Use whatever works for you.

### Color

Next, we can start choosing some colors. You can use colors from your mood board, colors that are part of your organization's brand, or come up with something new.

Your main color might be something commonly associated with your field. For example, blue is often associated with efficiency and trustworthiness, and green is associated with nature and money.

To add interest while keeping things from becoming too chaotic, we can come up with a color scheme.

Some common color schemes include **triadic**, where we choose three colors that are as far away from each other on the color wheel as we can get, and **analogous**, where we choose colors adjacent to our main color.

![Examples of analogous color schemes using green](images/colors.png)

Notice that we can experiment with adding **value**, or various amounts of black, white, and gray, to produce variations of any color scheme. Adding black to a color makes it a **shade**, while adding white makes it a **tint**.

We'll also decide on the relative proportions of each color in our design. Many designers use a "main color" for 50-70% of the elements that have color, and one or two "accent colors" for the other 30-50%.

One accent color can also serve as the **call to action** color. This will mark interactive or important elements, such as links, buttons, and/or headings.

I'm going to use the purple and the green from the first triadic scheme, with the green as my main color and purple as my accent.

### Style guides

When we have a better idea of what we want, we can start to collect all of our elements in one place. An important tool for designers is the **style guide**.

Here's a sample from [Spotify's style guide](https://developer.spotify.com/branding-guidelines/).

![](images/spotify.png)

Style guides are often informal if your product is small, and it can be a work-in-progress that is developed as you work. Still, style guides are a good place to store design elements that you'll come back to again and again, such as colors, fonts, and, as we'll cover later in this workshop, components.

Storytelling and consistency go hand-in-hand. If you visited a website with five different fonts, eight different colors, and no consistent font sizes, you'd think they were pretty unprofessional. The overall experience would also be confusing and overwhelming.

So when you know you want something to stay consistent throughout, make a note of it on your style guide. This will be helpful to you, to your collaborators, and to developers.

Now that we have a plan for our aesthetics, how are we going to arrange the content on our page?

### Layouts

Layout is primarily about organizing information in a way that makes sense. Let's say that we're making a learning lab. We've got the project name, some mini games, and we need to provide some way for

Let's have a look at some popular layouts.

![Designs using one column include National Geographic](images/single-column.png)

**Single-column** 

Single-column design is probably the most popular design because it is so simple. You can take this literally, by having all of the content on your entire website on one column&mdash;but you might find that you need to split up the content into multiple pages, especially if you have a lot of content. 

In that case, each page itself can still have a single-column layout, if you want.

![Two-column design, such as Khan Academy](images/split.png)

**Multi-column/Split**

However, you might find that you want some content side-by-side on the same page view. Maybe you find the content to be equally important, and that one shouldn't come before the other. In that case, try a multi-column, or split design.

![](images/cards.png)

**Cards**

Sometimes you have a lot of the same type of thing that you want to offer the user as choices. That's where cards come in.

![](images/sidebar.png)

**Sidebars**

Finally, many designs have a static sidebar containing links on the right- or left-hand side, with the main content filling up the rest of the screen.

Many other designs are combinations or variations of these four basic designs.

#### A note on responsive design

The reality is that most websites today are visited on the phone.

If you're making a mobile app, you probably won't need to worry about how things look on the desktop, and ditto if you are making a complex interactive website that you don't expect people to visit on their phones.

However, most webpages, especially informational webpages about products, or apps that are designed to run on desktop and mobile, will require you to think about **responsive design**. That means that your content should, at the minimum be able to resize to desktop or mobile sizes while retaining all functionality.

![](images/responsive.png)

Many designers today use the "mobile first" philosophy, meaning that we try to make a fully functional design using a mobile layout *before* thinking about desktop layout.

This makes sense, since at the mobile level, design real estate is *much* more limited, and it's easier to adapt something constrained (mobile) to something less constrained (desktop) than the other way around.

For the first iteration of our learning labs, we're not going to worry too much about responsive design. However, this is a good design concept to keep in mind for future projects.

## Creating a wireframe

Finally, we get to use Figma. Press `F` or select the Frame tool from the menu bar and click on your workspace to create a frame. On the right side, in the options panel, you'll find that you can click on the Frame dropdown menu and choose a preset size.

![](images/frame.png)

I'm going to choose the Desktop preset.

Now, we can start adding content. Use the Shape tools, the Text tool, and the Pencil tool in the menu bar to draw and write whatever you like. (You might have to press the dropdowns to get the tool you want.)

Fill colors and fonts can be applied from the Options panel.

You'll often want to group elements together so that they can move around together. Press `Ctrl` + `G` to group selected elements. Notice that in the layers panel, the elements appear to be "children" of a folder, which you can rename however you like.

![](images/group.png)

I'll be referring to frames and groups throughout this document. Frames are kind of like fancy groups, which we'll explore more soon.

Remember that groups are marked with a dotted rectangle icon in the layers panel, while frames are marked with a hash. An indented element is the child of the nearest group or frame.

### Alignment

There are basically two ways to do layouts in Figma: automatic and manual.

Auto-layout can be turned on by pressing `Shift` + `A`. In the options panel, you'll find choices for . Auto-layout can be very convenient when you're wireframing, or when you have multiple similar elements .

It's just what it sounds like: you don't have to waste time worrying about where to put elements or what spacing to use!

![](images/auto-layout.png)

Auto-layout applies only to the parent of a group. That means that layers within grouped objects won't be affected by auto-layout. To use it effectively, avoid applying it to the entire frame&mdash;use it with individual groupings of elements.

For complex and less predictable layouts, use the alignment buttons at the top of the options panel. These alignments always apply to the nearest parent frame.

![](images/align.png)



## What makes good design?

Web products have two main functions: to catch and maintain people's attention (aesthetics) and to give them information (function). One cannot come at the expense of another.

**User experience (UX)**, at its basic definition, involves making sure that the products we make are intuitive and easy to use. At a higher level, it is the art of balancing function and aesthetic.

Psychology informs much of UX design. Where will a user look first? How long will they stay on a page before getting bored? Do they know that a button is clickable? These are all considered UX questions.

While UX principles are largely out of scope of this workshop, the best way to get good is to ask for feedback from your friends and family. They're quite good examples of real users!

However, the minimum requirements for good communication will differ for different users, which may not be represented by immediate friends and family. These considerations are collectively called **accessibility**, which we will discuss in a later workshop.

Successful UX design will be accessible, and vice versa.

### Readable body text

The worst designs that I see usually involve unreadable text. Remember when I said that there are some rules that you really shouldn't get creative with? Well, anything to do with body text (that is, the main content of your page, such as an article or blog post) should not be messed with.

(Not to name names, but Wikipedia and art school websites are common culprits.)

For example, something that I would not want to read:

![](images/bad-text.png)

Books are printed the way they are for a reason: they provide an incredibly comfortable reading experience. News sites are some of the best examples of readable text, because their entire business model is based off of readability.

Here is an example of the same text, with print-like formatting applied.

![](images/good-text.png)

My criteria for readable body text therefore include:

* 15-20 words per line
* Sans-serif or serif font
* High-contrast such as black on white (dark mode, while popular, actually strains your eyes.)
* At least 18pt font for desktop, 20pt for mobile
* Around 1.5 leading (line spacing)

### White space

You'll notice that many of the above guidelines revolve around having a ton of negative space in the design. "Designs need room to breathe" is a quote I remember from somewhere.

White space can be used to bring out an important piece of text (see the Apple website below), by using the contrast between empty space and, well, not-empty space.

![](images/apple.png)

As the Apple website illustrates, just because we have a lot of "screen real estate" does NOT mean that we should fill it up. Users become psychologically overwhelmed if we give them too much information at once. Simpler is usually better&mdash;with that being said, though, simplicity does not have to come at the expense of aesthetics.

And again, consistency is also important in spacing.

The left image below shows a spacing (often called gutters in print publishing) of 50px between elements, while the right image has no set spacing at all.

![](images/spacing.png)

## Basic prototyping

Prototyping refers to making a version of your app or website with interactive components. After this section, you should be able to make clickable buttons and links that lead to new pages in your prototype, allowing developers to get a better sense of the functionality of your vision.

### But first, components

Components are central to Figma. Consistent, reusable components are a win-win-win: they're ultimately easier on you, on developers, and on users.

Let's say we want to make a few cards on the landing page for our activities. Draw a square, and add some text calling it Activity 1. Select these elements and press `Ctrl` + `Alt` + `K`. You just created your first component!

`Alt` + drag this component to duplicate it. Notice that in the layers panel, the component has a purple icon with four diamonds, but the duplicated **instance** has only a hollow diamond. This means that the instance will live-update to match the parent component.

Try it out: change the font size of the parent, or the color. The instance immediately updates to match. However, it doesn't work the other way: overriding the color of an instance does not affect the parent.

*This means that if you change your mind about an element, you only have to make changes once and every page will update to match.* Components are an incredibly powerful (ie, time-saving) tool.

![](images/component.png)

(Note: to keep content from spilling off the frame, check the "clip content" box in the options panel under the Frame section. This is what I meant when I said frames are special groups.)

*Before* you start duplicating your pages to begin prototyping, look over your design and try to predict what will be helpful to future-you. I always make the header and footer into components, as well as the background if applicable. Other elements are up to your discretion.

If you plan on reusing any piece more than once throughout your design, make it a component. It's easier to detach an instance from its parent (`Ctrl` + `Alt` + `B`) than to go through 20 pieces trying to update them all to match.

Let's make the header and footer into components now, so that when we want to make more pages for our website, we can just duplicate our home page and edit the copy, knowing that any changes we need to make to the header and footer later will be updated on all pages.

### Making connections

Okay, we're all missing that during COVID-19. But, maybe we can fill a little of that void in our lives by making some FIgma connections.

Press `Ctrl` + `D` to duplicate our main page. Add some body text (called "copy" in UX-speak). This will be our "About" page.

![](images/duplicate.png)

On the top of the options panel, you'll see a Design tab. Switch over to that, and click on the workspace so that nothing is selected. You'll see that there is an option to set a starting screen; set that to our Home page.

![](images/start.png)

Next, in your Home page frame, select the text in the header that says About. Notice the blue node on the right-hand side of the text box.

Drag this node to the About frame until it snaps (be careful to direct the arrow to the entire frame, not any of its contents).

A pop-up should show up with many different options, although the current selections will do for our purposes. The "on click" indicates that when the user clicks the About link, the prototype will display the About frame&mdash;kind of like an interactive presentation.

![](images/prototype.png)

You've made your first prototype connection! This should be enough to get you started with a linear flow, although Figma has many powerful functions associated with prototyping.

### Content organization

Which pages do we connect in our prototype, and in which order? This is where we have to think about content flow.

Let's return to the concept of storytelling. When a user enters your site or app, they are being introduced to a new environment. They might not quite know what they want, or they might be looking for a specific thing.

So, we should ask ourselves: how is a user going to navigate your website? Let's start by mapping out some possibilities from the pages that we plan to include. Which option below looks easier to navigate?

![](images/flow.png)

Generally, the more levels you have in your hierarchy, the more clicks it will take for the user to get to what they want, and the more frustrated they'll become. Again, we want to smooth the path for our users. So, in this case, the option on the left is easier to use.

However, there are instances where having 20 pages at the same level doesn't make sense. You might want to put more general pages at the first level after the home page, and use those general pages as folders to organize more specific pages.

![](images/flow2.png)

You can build content organization into your prototype by creating submenus within your menu.



![](images/nyt.png)

Or, you can make certain pages only accessible through links on the parent page (for example, "forgot password" should only be accessible from the "login" page).

Organizing content might take a lot of drawing and erasing, and more than a few rounds of feedback from users, but your work pays for itself in terms of user experience.

### Nice work!

You now have a basic prototype! Press the Play button at the top right of your workspace to preview your prototype. You can send this link to others for a high-level overview of the project.

![](images/play.png)

As a final note, the Inspect tab next to the Prototype tab is useful for developers.

![](images/inspect.png)

## Sources and further reading

* [Web layouts (Nick Babich/Adobe XD)](https://xd.adobe.com/ideas/principles/web-design/11-website-layouts-that-made-content-shine-in-2019/)
* [Content organization (Lauren Hooker/Elle and Company Design)](https://www.elleandcompanydesign.com/blog/organizing-content)
* [Color theory (Christian Vizcarra/UX Collective)](https://uxdesign.cc/all-you-need-to-know-about-colors-in-ui-design-theory-practice-235179712522)
* A really cool feature we didn't have time to cover today: [Constraints](https://help.figma.com/hc/en-us/articles/360039957734-Apply-Constraints-to-define-how-layers-resize)

### A note on keeping up

As you know, things on the web are never permanent. To keep up with the trends, I recommend just staying aware of changes that are happening around you. As you're browsing the web, ask: Why did Google change their icons again? What does the new iPhone look like?

Additionally, the Community tab on your Figma home page is a great place to find neat things that the community is creating. (Similar sites include [dribbble](https://dribbble.com) and [Behance](https://www.behance.net).) You can also find inspiration from artists working in other media on Instagram, Pinterest, and more.

For skills- and feature-related tips and tricks, Figma recently changed the location of their community forum from [Spectrum](https://spectrum.chat/figma) to the [Figma Support Forum](https://forum.figma.com/). Check it out to explore advanced Figma topics!

### Keyboard shortcuts

Click the question mark at the bottom right hand corner of your workspace and click Keyboard Shortcuts for a full list. These are the ones that I use every day. They will save you literally hours.

| Shortcut                  | Function                                                     |
| ------------------------- | ------------------------------------------------------------ |
| `K`                       | Select scale tool (resizes objects proportionally)           |
| `C`                       | Select comment tool                                          |
| `V`                       | Select mouse tool                                            |
| `P`                       | Select pen tool                                              |
| `Alt` + `Enter`           | Post the current comment                                     |
| `Alt`                     | Press when resizing or drawing to draw from center. Press before dragging to duplicate |
| `Shift`                   | Press to resize proportionately, to draw regular polygons, or to snap lines and anchors to 45-degree angles |
| `Shift` + `H`             | Flip horizontally                                            |
| `Shift` + `V`             | Flip vertically                                              |
| `Ctrl` + `D`              | Duplicate in place                                           |
| `Ctrl` + `G`              | Group                                                        |
| `Ctrl` + `Shift` + `G`    | Ungroup                                                      |
| `Ctrl` + `E`              | Flatten a group of shapes into one vector                    |
| `Ctrl` + `Y`              | Redo                                                         |
| `Ctrl` + `R`              | Rename or batch rename                                       |
| `Ctrl` + `Alt` `C`        | Copy properties (fill, stroke, etc.)                         |
| `Ctrl` + `Alt` + `V`      | Paste properties                                             |
| `Ctrl` + `\`              | Toggle menu show/hide                                        |
| `Ctrl` + `Alt` + `G`      | Frame current selection                                      |
| `Ctrl` + `Alt` + `K`      | Create a component from current selection                    |
| `Ctrl` + `Alt` + `B`      | Detach instance of a component                               |
| `Ctrl` + `Shift` + `H`    | Hide/show current selection                                  |
| `Ctrl` + `Shift` + `Lock` | Lock/unlock current selection                                |
| `Ctrl` + scroll           | Zoom in and out                                              |
| `Space` + drag or scroll  | Pan around the screen                                        |
