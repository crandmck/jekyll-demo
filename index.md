---
layout: default
title: "Jekyll Demos: Admonitions"
---


Use the following "admonition" styles to call out special information.

## Tip

This markdown:

```
Here's a handy tip that may help you out.
{: .tip }
```

Yields:

Here's a handy tip that may help you out.
{: .tip }

Unfortunately, this only works for single-line markdown (i.e. a basic paragraph).  If you need to use something like a bullet list in an admonition, you have to use a hack like this:

```
Do it this way:<br/><br/>**&bull;** Step one. <br/>**&bull;** Step two. <br/>**&bull;** Step three.
{: .tip }
```

Do it this way:<br/><br/>**&bull;** Step one. <br/>**&bull;** Step two. <br/>**&bull;** Step three.
{: .tip }

Unfortunately, just using a `div` doesn't work that well (I'm sure there's some CSS that could fix this):

<div class="tip" markdown="1">
Do it this way:
- One
- Two 
- Three
</div>


## Info

This markdown:

```
Here's some useful information.
{: .info }
```

Yields:

Here's some useful information.
{: .info }

## Note

This markdown:

```
Take note; this is some information you need.
{: .note }
```

Yields:

Take note; this is some information you need.
{: .note }

## Warning

This markdown:

```
Danger, Will Robinson! This is a warning you should heed.
{: .warning }
```

Yields:

Danger, Will Robinson! This is a warning you should heed.
{: .warning }
