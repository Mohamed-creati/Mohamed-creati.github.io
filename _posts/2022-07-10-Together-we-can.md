---
title:  "I can, so I did"
mathjax: true
layout: post
categories: media
---

![Let's jump out of something](/assets/skydive.jpg)


I know I cannot believe this view too.



## Code

Embed code by putting `{{ "{% highlight language " }}%}` `{{ "{% endhighlight " }}%}` blocks around it. Adding the parameter `linenos` will show source lines besides the code.

{% highlight c %}

static void asyncEnabled(Dict* args, void* vAdmin, String* txid, struct Allocator* requestAlloc)
{
    struct Admin* admin = Identity_check((struct Admin*) vAdmin);
    int64_t enabled = admin->asyncEnabled;
    Dict d = Dict_CONST(String_CONST("asyncEnabled"), Int_OBJ(enabled), NULL);
    Admin_sendMessage(&d, txid, admin);
}

{% endhighlight %}

## Two feet safely on the ground

I can say for sure it was the most exhilirating, awe inspiring experience that no ride may ever compare to. I would be ernst enough to say I may not want to tempt fate again. However, you never know what the future has for you, I could be skydiving with the SAS for a top secret mission. 

![Safe and Sound](/assets/skyjump.jpg)

[After the skydive}

## Embedded content

You can also embed a lot of stuff, for example from YouTube, using the `embed.html` include.
{% include embed.html url="https://www.youtube.com/embed/_C0A5zX-iqM" %}
https://www.youtube.com/watch?v=sDSOOtWAF0k
