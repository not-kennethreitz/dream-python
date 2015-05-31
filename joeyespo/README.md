Dreams
======

My Python dreams, and my reasons for them.


## The community

- No [judgment](http://sivers.org/ss) or [ridicule](http://harthur.wordpress.com/2013/01/24/771/)

- Community [open](http://dcurt.is/what-a-stupid-idea)-[mindedness](http://signalvnoise.com/posts/3124-give-it-five-minutes)

- More [art](https://www.youtube.com/watch?v=ikAb-NYkseI) (requires the previous two)

- More creative uses of Python (requires the previous three)

- Welcome all developers from all backgrounds

- For Pycon to come to Pittsburgh, PA :smiley:


## The language

- **No more Python 2 vs 3**

  This, hands down, is the most common reason I see new developers
  looking past Python.

  The polarized nature of this debate is distracting. It's possibly the most
  damaging decision the Python community has ever been faced with, but it's
  also a reality and we need to figure out a sensible solution. This requires
  some creative thinking.

  I personally feel the effort spent *forcing* people to upgrade is a lost
  cause. It's swimming upstream. It's wasting energy. It's also unrealistic
  to expect the open-source community to embrace such a giant leap all at once.

  Even though I acknowledge Python 3 is a better language, there's still
  not a *compelling* reason to make a full jump. Worse, *even if there was* a
  compelling reason, you still can't force it to happen. It's the equivalent to
  switching to a new language. It's also complicating some very respectable
  projects. Instead, we need to continue to *slowly* back-port Python 3 to
  Python 2. Let people naturally evolve and upgrade at their own pace (read: by
  how much extra time they have). Eventually, the Python 2 / 3 gap will be
  closed and devs can then make that final step to 3. No jumping necessary.

- **Npm-like packaging system**

  When new people look to Python, this is a close 2nd for why they decide not
  to dive in. The packaging system is overwhelming and an unnecessary obstacle.
  Even though virtualenv helps and even [becomes easy][easy] after a while,
  it's still over-complicated and adds a hoop to the daily routine.

  In comparison, Node has always been an extremely pleasant experience. It has
  always worked seamlessly without issue. More specifically, it's instant
  (`npm install x`), self-contained (everything installs locally), and there's
  no hoops to jump through to *simply start hacking on a different project*.

- **PyPy by default**

  PyPy is awesome. And *fast*. Enough said.

- **Python in the browser**

  A lot of what I do these days is web development. Because of this, I've
  slowly been migrating to JavaScript. It's been a fragmented experience
  compared to the thoughtfulness of Python data types, literals, and other
  out-of-the-box language features that cover most daily tasks well.

  However, because JavaScript is maturing (EcmaScript 6, which I actually enjoy
  quite a bit!), and because it's still the only practical option for working
  in the browser, JavaScript is inevitable. Browsers are improving daily, and
  tools like Angular and Ember make rich web application development extremely
  approachable. Services like Firebase remove the need for server code
  entirely. More importantly, browsers still have the most reach today, and we
  need to adapt. I've personally been adapting in my choice of language.
  However, if Python adapted instead of myself, I'd be more than happy to stay.

  Don't get me wrong. Flask and Requests are still **an absolute joy to use**.
  Today's JavaScript frameworks don't even come close. However, the JavaScript
  frameworks are getting better. There will be fewer and fewer reasons to use
  Python on the backend. I truly believe if we want Python to be relevant for
  web, we need *more* than server-side improvements. We need client-side Python.


## Bonus

- **The return of the `print` statement**

  I know, I know. Humor me, I'm dreaming. This feature was always a
  beautiful part of the Python language to me though.

  Also, the `print` statement makes teaching a *much more pleasant experience*
  for everyone involved. No more explaining to the student why
  they need to adhere to the strict nature of parentheses. Save that for more
  advanced topics like writing and calling functions. The absolute minimal
  syntax is why I keep using Python 2 for an introduction to programming.
  It's minor in the day-to-day, but when teaching someone who has no prior
  experience, the syntax errors are indeed frustrating.

  Python has always been in favor of readability and dev experience. It
  seems odd that in this case, simplifying the language's **definition**
  is more important. Most people don't care about that. (Except perhaps
  when you need to print in a lambda. But why not introduce an
  `os.out()` instead of breaking language compatibility?)


## Closing thoughts

I recognize that these are impossible dreams. Even borderline controversial
in the Python community. However these are my dreams.

If you share the same dream, feel free to [reach out on Twitter][twitter].

Kennith, thank you for this outlet. The simplicity of this repo is profound,
and I've enjoyed reading the wishes of others. :smiley:


## Update: Shared dreams

Here's some dreams I didn't even know I had until reading what others had to say.

- Pattern matching like rust ([thikonom](https://github.com/kennethreitz/dream-python/tree/master/thikonom))
- Native distributables ([rosarior](https://github.com/kennethreitz/dream-python/tree/master/rosarior))
- go fmt ([iandanforth](https://github.com/kennethreitz/dream-python/tree/master/iandanforth))


[Pittsburgh]: http://en.wikipedia.org/wiki/Pittsburgh
[easy]: http://www.infoq.com/presentations/Simple-Made-Easy
[learnable-programming]: http://worrydream.com/LearnableProgramming/
[logging]: http://12factor.net/logs
[twitter]: http://twitter.com/joeyespo
