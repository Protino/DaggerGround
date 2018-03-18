# What is Dagger

It is a Dependency Injection framework(??) by Google Inc.

## Dependency injection

- Injecting dependencies rather than creating them yourself. (Using `@Inject`)
- Asking someone else to give us the needs. (i.e, `@Component`)
- Telling the world( or @Component) that I'll provide the dependencies (`@Module`). Functions

This is what I could figure out from
- [Gregory Kick - Google Talk](https://www.youtube.com/watch?v=oK_XtfXPkqw)
- [Patrick Hammond - GDG Talk](https://www.youtube.com/watch?v=cA4iEmWuSB8)
- [Dagger 2 for Android Beginners](https://medium.com/@harivigneshjayapalan/dagger-2-for-android-beginners-introduction-be6580cb3edb)

## Plan

Build an android app using Dagger2.

What to build?

- Weather app? Classes - Weather, Location, 
- Todo app? Classes - Note, Dashboard/ Collection, Form/Editor, NoteType
- Music app. This might get complicated soon with stuff that is completely unrelated to Dagger and we might spend more time on Media session, media this and that.
- Blindchess app. Interesting because of lots of classes - Piece, Board, Move, Engine, Player....
- Memes?

    ![LOOOOOOOOOOOOOOOOL](https://media.giphy.com/media/LLHkw7UnvY3Kw/giphy.gif)

<hr/>

<!-- Disqus stuff-->

<div id="disqus_thread"></div>
<script>

var disqus_config = function () {
this.page.url = 'https://protino.github.io/DaggerGround/'
this.page.identifier = '/DaggerGround/'
};
(function() {
var d = document, s = d.createElement('script');
s.src = 'https://https-protino-github-io-daggerground.disqus.com/embed.js';
s.setAttribute('data-timestamp', +new Date());
(d.head || d.body).appendChild(s);
})();
</script>
<noscript>Please enable JavaScript to view the <a href="https://disqus.com/?ref_noscript">comments powered by Disqus.</a></noscript>
                            