# Represent

Markdown driven presentations for humans

> Represent | Representer | Deckdown | Powerdown | Markdeck


## What is Represent?

* Represent takes github-flavoured markdown documents and presents them as slide decks for presentations, documents with speaker notes and code included inline.

##

## Slide title

> This is some speaker notes

### Slide text

## New slide with just an image

> Speaker notes to explain the mind explosion image

> How do we resize the image?

![Mind Explosion](mind_explosion.gif) ? fullscreen | background

> We need some extra metadata for images to specify location and sizing

* Background
* Background with overlaid text
* How do images get displayed in document mode

## New slide with code

> Explain code, it should be indented or can be triple back ticked

    <div class="reveal">
      <div class="slides">
        <section>Single Horizontal Slide</section>
        <section>
          <section>Vertical Slide 1</section>
          <section>Vertical Slide 2</section>
        </section>
      </div>
    </div>

> Code should be auto detected but if you need to specify use this format

```html
<section data-markdown>
  <script type="text/template">
    ## Page title

    A paragraph with some text and a [link](http://hakim.se).
  </script>
</section>
```

## Tests for slide code

* Separate file?
* Inline?
* Code that can run in the slide

## Speaker notes

* Timer
* Speaker notes
* Websockets to communicate between browser windows
* Can edit code or presentation without showing the audience
* Chris Lloyd mode (tm) can pretend to live code
