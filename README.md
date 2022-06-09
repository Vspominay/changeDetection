<h1 align="center">🕵️ Change Detection </h1>

<h2 align="left">Functions</h2>

### Just as with `ngOnChanges` the `ngDoCheck` lifecycle hook is triggered `even if the component uses OnPush strategy`.



## [Change detection order](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular#change-detection-operations)

- [x] **[Detach](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular#detach)**
>This ensures that during the following change detection runs the branch ```will be skipped```


- [x] **[Reattach](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular#reattach)**
>Can activate change detector <i>**for the current**</i> component ```to run change detection``` and detach it on the next tick


- [x] **[MarkForCheck](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular#markforcheck)**
>We need a way to enable check for ```all parent components``` up to root component. And there is a method for it markForCheck


- [x] **[DetectChanges](https://indepth.dev/posts/1053/everything-you-need-to-know-about-change-detection-in-angular#detectchanges)**
>There is a way to ```run change detection once``` for the current component and all its children.


<h2 align="left">Binding and view</h2>

- [x] **[More info](https://indepth.dev/posts/1058/a-gentle-introduction-into-change-detection-in-angular#component-views-and-bindings)**

<h2 align="left">NgZone</h2>

- [x] **[More info](https://indepth.dev/posts/1058/a-gentle-introduction-into-change-detection-in-angular#automatic-change-detection-with-zones)**

>    Using NgZone to run some code outside of Angular<br> to avoid triggering change detection is a common optimization technique.
