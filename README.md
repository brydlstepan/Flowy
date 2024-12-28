# Flowy
Modern Jellyfin Theme
(Currently a Work in Progress)


Paste the following code in the Custom CSS code box:

```css
@import url("https://cdn.jsdelivr.net/gh/brydlstepan/Flowy@main/Style.css");
```
To adjust varriables like colours, radiuses etc, you can also add the following code and adjust the varriables to your taste:

```css
:root {
    --Accent: #fc424a;
    --PrimaryBg: #1a1c1e;
    --SecondaryBg: #121314;

    --TextColorMain: rgba(255, 255, 255, 0.8);
    --TextColorSecondary: rgba(255, 255, 255, 0.5);

    --GlassBg: #202225cf;
    --GlassBorder: 1px solid #ffffff08;
    --GlassBorderRadius: 0.65em;
    --GlassBlur: blur(10px) invert(2%);

    --CardBorder: 1px solid #ffffff0d;
    --CardBorderRadius: 0.65em;

    --InputBorder: 0.15em solid #1f2123;
    --InputBorderActive: 0.15em solid #272a2e;
    --InputBorderRadius: 0.5em;


    --Shadow: 0 1px 2px rgb(0 0 0 / 90%), 0 0px 2px rgb(0 0 0 / 90%);

    --danger: #D32F2F;
    --warning: #FBC02D;
}
```
