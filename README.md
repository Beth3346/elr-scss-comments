# elr-scss-comment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-comment.svg?style=flat)](https://www.npmjs.com/package/elr-scss-comment)

a library of sass mixins

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-comment --save
yarn add elr-scss-comment
```

```scss
@import "~elr-scss-comment";

.elr-comments {
  @include elr-comments;
}
```

```html
<div class="elr-comments">
  <div class="elr-comment">
    <figure class="elr-comment-avatar">
      <img src="/images/avatar5.jpg" />
    </figure>
    <div class="elr-comment-content">
      <div class="elr-comment-heading">
        <h3 class="elr-comment-author">Joe</h3>
        <p class="elr-comment-timestamp">10 minutes ago</p>
      </div>
      <div class="elr-comment-body">
        <p>This article is so interesting!</p>
        <a class="elr-comment-reply" href="#">Reply</a>
      </div>
    </div>
    <div class="elr-comment elr-comment-nested">
      <figure class="elr-comment-avatar">
        <img src="/images/avatar1.jpg" />
      </figure>
      <div class="elr-comment-content">
        <div class="elr-comment-heading">
          <h3 class="elr-comment-author">Kate Brewster</h3>
          <p class="elr-comment-timestamp">Just Now</p>
        </div>
        <div class="elr-comment-body">
          <p>Yes! this site always has the best articles.</p>
          <a class="elr-comment-reply" href="#">Reply</a>
        </div>
      </div>
    </div>
  </div>
</div>
```

## License

SEE LICENSE IN LICENSE.md
