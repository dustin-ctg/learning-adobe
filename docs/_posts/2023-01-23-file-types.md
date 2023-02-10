---
title: All About File Types
description: This post is going to cover most of what you need to know about file types, what they mean, and when to use which type.
date: 2023-01-23 16:50:00 -0500
categories: reference
---

# Howdy Howdy

We're going to cover a few different file types, and when to use what to make sure your designs look their best in every environment. A lot of the web apps available online don't typically inform their users what file types they need for certain design jobs, and it can and often does lead to some pretty crusty results in the final designs.

Our main topics will include:
- [Howdy Howdy](#howdy-howdy)
	- [Vector vs Raster](#vector-vs-raster)
		- [Vector](#vector)
	- [File Types](#file-types)
	- [Print vs Web](#print-vs-web)
		- [When Your Design Goes to Print](#when-your-design-goes-to-print)
		- [When Your Design Goes Online](#when-your-design-goes-online)

## Vector vs Raster

Vector files and raster files are both types of image files, but they have an important distinction between them that makes them useful for different design purposes.


### Vector
---
Vector
: In a nutshell, vector files are ***image files that are created using math***. Kind of like knowing how to find the circumference of a circle (2πr) can help you draw one, computers use reference points and calculations that are stored in vector files to recreate an image. It can also be thought of as giving a computer the recipe to replicate a dish. These images can be scaled up or down without ever losing quality.

Examples: .pdf, .svg, .ai, .eps

Raster
: Raster files are ***what we would commonly refer to as "pictures" or "photos"***. These are typically pixel-based image files that possess a fixed array of dots (pixels), which store information about color, and sometimes transparency. These images will likely lose quality when scaled up (and down, in some cases).

Examples: .jpg, .png, .gif

> There is also a subset of raster image files called "RAW" files, which are image files that store the data captured by a digital camera's sensor at the time that a photo was taken; these typically require special software to open and edit. We'll be using RAW files later on in our designs.
>
> Examples: .NEF, .CR2, .ARW

## File Types

.JPG/.JPEG
: Short for "**Joint Photographic Experts Group**", which is the organization that standardized the file type in the 1980s. This is a standard photo; it's a relatively good way to store images that don't need to be printed, and don't need any form of transparency, but it will likely suffer quality loss when exported from an original artwork, or uploaded to online platforms.

.GIF
: Short for "**Graphics Interchange Format**". This was the standard on the web in the late 80s, and is still used today for fun little animations on the web. In a nutshell, it uses math to read information about an image (or a set of images), replace the repetitive parts with instructions ("Repeat this set of pixels, at these locations, at this time"), and allows for transparency ("These pixels will not contain any data. Either default to white, or keep them empty."). This process is called "**lossless compression**".

.PNG
: Short for "**Portable Network Graphics**". This was created as a replacement for GIFs. It dropped support for animations in favor of improved compression capabilities. It still supports transparency, so it's generally going to be a bigger file than a .JPG, but it will generally also scale a lot better (on the web) than a .JPG will.

.AI
: Short for "Adobe Illustrator", which is a vector-based file format. Vector files are made up of mathematical equations, making them infinitely scalable without losing quality. This makes AI files great for logos, illustrations, and icons.

.PSD
: Short for "Photoshop Document". This is a raster-based file format, making it great for photo editing and manipulation. Raster files are made up of pixels, making them limited in scalability and prone to losing quality when enlarged.

.PDF
: Short for "Portable Document Format". This file format is versatile, as it can be both vector and raster-based, making it great for printing and sharing designs. PDF files can contain a variety of information, including text, images, and vector graphics.

.EPS
: Short for "Encapsulated PostScript". This is a vector-based file format that is commonly used for printing and creating logos, illustrations, and icons. EPS files can be opened and edited in Adobe Illustrator, as well as many other vector graphics editors.

.SVG
: Short for "Scalable Vector Graphics". This is a vector-based file format that is optimized for the web. SVG files are scalable and can be easily edited and resized, making them great for logos, illustrations, and icons that need to be used on the web.

.TIFF
: Short for "Tagged Image File Format". This is a raster-based file format that is commonly used for printing high-quality images, such as photos and graphics. TIFF files are typically larger in size compared to JPG or PNG files, but they are also higher in quality and can be easily edited and manipulated.

## Print vs Web
---
A good habit to keep for all your projects is to design with purpose - is this design going to be printed or displayed on the web? The difference in resolution is a huge factor, as print designs typically require a higher resolution than web designs. Print designs need to be at least 300 dpi (dots per inch), while web designs only need 72 dpi. Different file types are suited for different purposes. When you're designing, you usually want to think about what file type is going to be used to display the final design.

### When Your Design Goes to Print
If you aren't printing photos specifically, and your design doesn't make heavy use of photography, you'll almost always want to print using a pdf file.

### When Your Design Goes Online
If you're designing an icon for online use on a website, SVG is the best bet.
