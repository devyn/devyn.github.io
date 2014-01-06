---
title: Hello, world!
language: en
layout: post
---

Welcome to my blog!

{% highlight ruby %}
def foo
  puts 'hello, world'
end
{% endhighlight %}

<!--more-->

## How to refactor the strange rognoswark

{% highlight haskell linenos %}
module Rognoswark where

import Nartlsnark

data Rognoswark = Rognoswark Int

refactorRognoswark :: Rognoswark -> Maybe Nartlsnark

refactorRognoswark (Rognoswark n) =
  case n of
    _ | n < 0     -> Nothing
      | otherwise -> Just Nartlsnark

{% endhighlight %}

### `rognoswark-refactor(1)`

Fortunately, there's [a UNIX tool](http://example.com/) for that:
`rognoswark-refactor`. It automatically refactors rognoswarks and converts them
into the much lighter and more efficient nartlsnarks.

## Lorem ipsum text, as standard

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Curabitur nec mi erat.
Aenean in ultrices nisi. Morbi id mollis mi. In condimentum aliquet diam eget
pellentesque. Phasellus egestas purus quis ipsum ultrices tempor. Nam
ullamcorper, dui id porta congue, lectus augue dignissim velit, a adipiscing
nisi ipsum id ipsum. Quisque in velit ipsum. Ut in lectus bibendum, euismod quam
quis, fermentum libero. Quisque viverra aliquet metus sed venenatis. Mauris
rhoncus lorem ac semper semper. Quisque ac fringilla sapien. Proin at ipsum ut
lacus fringilla consectetur. Curabitur lectus metus, pretium id justo quis,
vestibulum tempor orci. Pellentesque pulvinar ipsum ac lorem pellentesque, sed
rhoncus odio aliquet. Maecenas quis tempor risus.

Nulla sem nulla, faucibus sit amet felis non, pretium consectetur est. Curabitur
luctus auctor sem, ut placerat purus rhoncus sagittis. Nunc ac lectus nec lacus
molestie accumsan ut sit amet odio. Praesent elementum odio eget sem mattis, a
venenatis magna dapibus. Vestibulum posuere rhoncus nisi sed sollicitudin.
Curabitur sodales urna urna, in gravida mauris sodales hendrerit. Maecenas in
sem quis augue consectetur aliquam. Aenean eu ornare nisl, vitae aliquam sapien.
Duis tincidunt sodales tellus, ac vulputate urna pretium sit amet. Integer
fermentum ligula et enim semper, at volutpat risus venenatis. Integer mattis
risus vehicula purus porttitor euismod. In sed adipiscing mi. Aenean facilisis,
eros ac porta adipiscing, quam diam laoreet libero, a rutrum arcu eros ut felis.
Morbi arcu velit, congue sed lectus a, adipiscing laoreet magna. Ut at auctor
elit. Etiam sagittis lectus id elit mollis volutpat.

> Maecenas bibendum elementum interdum. Proin elementum mollis eros, vel
> dignissim neque accumsan quis. Praesent ultrices laoreet purus vestibulum
> placerat. Duis metus eros, malesuada rutrum nunc quis, fringilla hendrerit
> tortor. Vivamus sapien tortor, malesuada id mollis sit amet, sodales nec elit.
> Praesent fringilla id elit ut placerat. Praesent non mauris porta dolor
> ultrices dictum.  Proin vel ante in massa eleifend commodo eu sit amet sem.
> Quisque placerat massa sit amet sagittis lacinia. Fusce sollicitudin risus
> adipiscing, congue diam quis, vestibulum dui. Sed hendrerit tellus eu enim
> placerat pellentesque.  Praesent tempor fermentum purus quis viverra.
>
> --- <cite>[De finibus bonorum et
> malorum](http://en.wikipedia.org/wiki/De_finibus_bonorum_et_malorum)</cite>

Aenean condimentum posuere lacus, pellentesque ornare lorem interdum eu. Vivamus
vehicula mattis mauris in consequat. Nulla aliquam consequat laoreet. Ut
pulvinar rutrum justo, nec rutrum odio placerat et. Curabitur ornare scelerisque
mauris, quis euismod nisl faucibus quis. Donec at nisi euismod, luctus leo id,
lobortis erat. Aenean elementum suscipit nulla, a pharetra risus mattis nec.
Proin nulla quam, varius id metus in, ornare aliquet nisl. Nam consequat nisi
risus, eget bibendum dolor pulvinar adipiscing. Vivamus magna ipsum, condimentum
tincidunt dolor eu, luctus mattis nisi. Nullam varius nisl sapien, vitae viverra
leo rhoncus auctor. Integer nec sem elementum, varius arcu eget, pulvinar ipsum.
Donec placerat suscipit risus, non porta libero iaculis et. Morbi porta tempus
enim, quis tempus lectus varius a.

Sed suscipit libero metus, et mattis nisi porttitor in. Etiam quis congue sem,
sollicitudin rhoncus ipsum. Suspendisse vel enim eget ipsum posuere tincidunt
sit amet id diam. Quisque eget purus justo. Nam vitae semper nisl. Cras feugiat
consequat turpis eu aliquam. Praesent at ante rutrum, interdum purus vitae,
ornare justo. Cras vel euismod mauris. Donec sodales risus sit amet elit varius
consectetur. Quisque id euismod sem. Integer ut justo in lectus eleifend laoreet
ac non sapien.
