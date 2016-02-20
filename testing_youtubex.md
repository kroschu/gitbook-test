gitbook-plugin-youtubex
===

<!--sec data-title="Introduction" data-id="intro" ces-->
This page is implemented using the two plugins developed by me: ```gitbook-plugin-youtubex```. Please check the [Github repo](https://github.com/ymcatar/gitbook-plugin-youtubex) for the syntax and changelog of the plugin.
<!--endsec-->

<!--sec data-title="Examples" data-id="example" ces-->
YouTube videos can be inserted into a GitBook chapter using a tag with the video id inserted in-between:
```
{%youtube%}dQw4w9WgXcQ{%endyoutube%}
```

It will appear like this:

{%youtube%}dQw4w9WgXcQ{%endyoutube%}

... which is responsive to the page size. A link will be displayed instead when exported to .pdf or other formats.

You can even embed time marker into the book:

* Never gonna run around {%m id="dQw4w9WgXcQ", s=47%}{%endm%}
* Never gonna give you up {%m id="dQw4w9WgXcQ", m=2, s=41%}{%endm%}

<!--endsec-->
