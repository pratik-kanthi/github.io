---
author: "Hugo Authors"
title: "Framework Opinions"
date: "2020-03-05"
description: "Framework Opinions"
tags: ["emoji"]
ShowToc: false
ShowBreadCrumbs: false
---

# Dethroning Frontend Frameworks

If you've been coding for the past decade, you can't deny that software has continually evolved. Thanks in part to Moore's Law, both our computational power and the complexity of software have surged. The developer experience hasn't been left behind, either.

Remember the days when we were stuck manually wiring up DOM events to HTML elements, hoping for a miracle in the form of a smoothly running web app? Ah, the nostalgia of typing `getElementById` with the precision of a concert pianist. Then came jQuery—our knight in shining armour. It was sleek, powerful, and reigned supreme for years in the web world.

Yet, despite its glory, jQuery had its limitations. It couldn't evolve into a full-fledged framework, largely because it was built on an imperative and event-driven architecture—two things that don't play nice with the highly concurrent nature of web apps.

There was a clear void for something superior, and to be fair, browsers weren't doing us any favours either. But here's my gripe (which, yes, is a bit of a rant): We've taken our yearning for better tools and rocketed it into the stratosphere, to the extent that it's causing more harm than good. It's intimidating for newcomers and exhausting for veterans, and that's a lose-lose for everyone in this ever-evolving game of web development.

#### Delightful beginnings
The precursor to this trouble started when Google introduced AngularJS, which I believe is **the most elegant, no-nonsense framework out there, even today**. It eliminated the event driven nature of web apps entirely by introducing two way data binding, a rock solid module system, while preserving pure HTML partials and a data layer on the frontend. I wonder why we stopped doing the latter one abruptly.
I still interface with a lot of early AngularJS code and it's always a delight. It does have it's problems, specially with the lack of tooling such as a bundler and all the luxuries that come with it. Regardless, it did set the stage for the next decade of web development.

### The underdog rises
With Angular making waves, other contenders like EmberJS weren't far behind, each bringing their own spin to make development easier—think better templating, CSS preprocessing, and task runners like Gulp. Then, tucked away in Facebook's labs, some devs had an epiphany. Why not just incinerate the DOM and rebuild it every time data changes? Sounds insane, but that's the magic of the virtual DOM, and it works like a charm. Your frontend can scale without giving you existential dread.

So along came **React**, flipping the JavaScript world on its head and setting a new standard for developer experience.

### Frameworks and How Their Fame-Works

But let's pump the brakes for a second. React and its cousins, like Vue and Svelte, have indeed broadened our horizons. But they've also thrust us into a never-ending whirlpool of "new and improved," where each year heralds the arrival of the next big thing. And so we leap, lured by the siren call of innovation, only to find that we're caught in a loop, much like a rerun of a TV show where the ending never changes.

If you were to tally up the hours spent discussing frameworks—Is Vue the new React? Should we use Svelte for the next project? Wait, you're still on Webpack?—you’d probably find we've collectively dedicated more cognitive real estate to frameworks than solving world hunger. And let's not even talk about the Server-Side Rendering (SSR) debates that spring up like mushrooms after a rainstorm—invigorating and toxic all at once.

When did Fear of Missing Out (FOMO) become a project management methodology? React's new hooks are out? Let's refactor everything! Wait, Vue 3 offers better performance? Burn the codebase! And so the wheel keeps spinning, like a hamster that's had one too many shots of espresso.

I wish I could cut out the mindless chatter about the next exciting JS project from my daily life as well as the HackerNews threads. I would miss out on nothing. Yet I know i'll find myself at another JS conference next year and talk about the same things while being queued up in a line for the buffet lunch.

### Have we lost the plot?
The never-ending loop of learning, adopting, and moving on to the next big thing feels eerily similar to the myth of Sisyphus, who was doomed to push a boulder up a hill only for it to roll back down, forcing him to repeat the process endlessly. The promise of a "final solution" to all frontend woes is always just over the horizon, never truly arriving.

![[https://ibb.co/ZSkCLRw]]

Albert Camus found some respite as he concluded "One must imagine Sisyphus happy" alluding to the idea that Sisyphus found happiness in the task of pushing the boulder up instead of the meaning of it.

However, today's developers are hardly content with the mere act of pushing the metaphorical boulder of frontend frameworks up the hill. Unlike Sisyphus, who might have found solace in the repetition, developers are often burdened by the looming dread of obsolescence. Each push—each new framework or technology—comes with the tacit understanding that it's just a matter of time before the boulder rolls back down, replaced by a newer, shinier boulder.

Camus might argue that we should find happiness in the journey itself, in the act of learning and adapting. But let's be honest: the existential comfort of Camus doesn't pay the bills, nor does it soothe the headaches of having to refactor an entire codebase just because the "new hotness" has arrived on the scene. What was once a space for creativity and problem-solving has increasingly become a treadmill of catch-up, where the joy of the craft is overshadowed by the anxiety of staying current.

So, while one could "imagine Sisyphus happy," today's developers might be better off imagining a world where the boulder stays put for a while, allowing them the freedom to step back, catch their breath, and perhaps even enjoy the view.


## Exciting things to look for
To conclude this rant disguised as a post, I would like to point towards some exciting projects that I think are a move in the right direction and they address some extremely important concerns when it comes to web development.

#### XState

**Why it's Cool**: For too long, state management has been a messy affair. XState brings structure to the chaos, utilizing state machines and statecharts to model complex logic in a visual and deterministic way.  This is grounded in computer and the idea that webapps are nothing but state machines.

**How it Addresses Concerns**: By focusing on finite states and transitions, XState nudges you towards a more predictable and testable codebase. It's like having a GPS for your app's state logic—no more wandering into the dreaded Forest of Spaghetti Code.

#### All JS First Libraries

**Why it's Cool**: Libraries like Date-fns, Lodash, and Ramda take a JavaScript-first approach, working seamlessly with native JS types and structures.  
**How it Addresses Concerns**: These libraries don't try to reinvent the wheel by introducing new paradigms or structures. They enhance what's already there, making it easier to write functional, efficient, and readable code without the cognitive overhead of learning a new "way of doing things."

#### Open UI

**Why it's Cool**: Open UI aims to standardize the wild west of UI components, providing a shared vocabulary and guidelines for building interoperable, accessible components.  
**How it Addresses Concerns**: The goal is to make UI development less about reinventing the wheel and more about actual user experience. It could be the Rosetta Stone we've been waiting for in the Tower of Babel that is frontend development.

#### Temporal API

**Why it's Cool**: Dealing with dates and times in JavaScript has often been akin to playing with fire while blindfolded. Temporal aims to simplify this by providing a robust, immutable date and time API.  
**How it Addresses Concerns**: By taking the complexity and pitfalls of date-time manipulation head-on, Temporal could save countless hours of debugging and hair-pulling, freeing developers to focus on, you know, actual features.


