<!-- Filename: Adding_an_image_to_an_article / Display title: Adding an image to an article -->

## Introduction

How best to add images to an article depends on which version of Joomla
and which editor are in use. This article has illustrations for Joomla
4 and 5 using TinyMCE, the Joomla default editor. To get started, open an
article for editing:

- **Select** **Content **→** Articles** in the Administrator menu.
- **Select** the title of the article you wish to edit

After inserting the article text, place the cursor at the location where
the image should appear.

## Adding a local image

If the image is located in the images folder of your Joomla installation
you should insert the image using the **CMS Content **→** Media** button
In the TinyMCE edit toolbar:

<img
src="https://docs.joomla.org/images/5/5e/Adding-an-image-to-an-article-cms-content-media.png"
decoding="async" data-file-width="1000" data-file-height="508"
width="1000" height="508" alt="select the cms content media button" />

In the popup window, navigate to the image you want to use and click to
select it. On selection a form will appear prompting for additional
data:

<img
src="https://docs.joomla.org/images/d/d4/Adding-an-image-to-an-article-selected-image.png"
decoding="async" data-file-width="1000" data-file-height="508"
width="1000" height="508" alt="the media select dialog" />

Set the image properties as required. In most cases you should certainly
fill out the Image Description (Alt Text) field. The other fields are
used to customise the image appearance with your own css.

- **Image Description**: This becomes the **alt** attribute for the
  image, an important feature for accessibility and compliance with web
  standards.
- **Image Class**: If an image is used without a caption some custom
  classes may be applied here. For example, **float-end ms-2 mb-1** will
  align the image to the right and float text around it with margins to the
  left and below to prevent text touching the image.
- **Figure Class**: If a caption is set then an alignment class, if any,
  should be applied to the Figure. It is a html tag that encloses the
  img tag. Note that in Cassiopeia margins are applied by the template
  style sheet.
- **Figure Caption**: Enables the caption which displays the Image Title
  below the image.

Select the *Insert Media* button to insert the image. The Insert Image
screen will close and the image will be displayed in the editor. Or
select the *Cancel* button to leave the Insert Image screen.

**Tip:** select the Toggle Editor button to see the applied Image and
Caption styles.

### Using Drag and Drop for Local images

You can drag an image from the desktop or
a file browser directly into the article text and the image will be
uploaded to the media folder and placed in the article. The only snag is
that all such uploaded images will be placed in the same media folder.
The location of the Images Directory used for upload and whether this
feature is enabled (On by default) are set in the TinyMCE configuration
Options.

## Adding a remote image

If the image you wish to use is not in the images folder of your Joomla
installation a slightly different procedure is needed.

- **Select** **Insert **→** Image** from the TinyMCE toolbar to open a
  dialog box.
- **Insert** the image url in the Source field.
- **Fill out** the other fields as required.
- **Advanced** provides some formatting options applied as in-line
  styles. Experiment with 1rem, 2, groove.

<img
src="https://docs.joomla.org/images/3/39/Adding-an-image-to-an-article-insert-edit-image.png"
class="thumbborder" decoding="async" data-file-width="480"
data-file-height="477" width="480" height="477"
alt="the insert edit image form" />

### Using Drag and Drop for Remote images

You can drag and drop an image from a remote web site directly into your
article text. But be aware that this may also copy the image container
html with class statements not valid for your site.

## Uploading images using the Insert Image screen

You may upload new images using the Media screen.

- First open the Media browser and navigate to the folder where you wish
  to store new images for the current article.
- Select the Upload button at the top left of the Media screen to open a
  file browser.
- Select the image files you wish to upload. Select Open in the file
  browser to confirm the selection. Note: The file browser style and
  layout depends on the browser and operating system you are using.
- The selected file(s) appear in alphabet order in the Media/Image
  screen.
- When the upload is complete a green confirmation notice will appear at
  the top of the screen.

You may now select and insert the uploaded image as before.
