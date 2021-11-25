# elr-scss-comment

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![npm](https://img.shields.io/npm/dm/elr-scss-comment.svg?style=flat)](https://www.npmjs.com/package/elr-scss-comment)

a library of sass mixins

## Installation

Download node at [nodejs.org](http://nodejs.org) and install it, if you haven't already.

```sh
npm install elr-scss-comment --save
```

or

```sh
yarn add elr-scss-comment
```

## Implementation

### Scss

```scss
@import "elr-scss-comment/src/main";

.elr-comments {
  @include elr-comments;
}
```

### HTML

```html
<div class="elr-comments">
  <div class="elr-comment">
    <div class="elr-comment-content">
      <div class="elr-comment-heading">
        <figure class="elr-comment-avatar">
          <img src="https://placekitten.com/200/200" />
        </figure>
        <div>
          <h3 class="elr-comment-author">Joe</h3>
          <p class="elr-comment-timestamp">10 minutes ago</p>
        </div>
      </div>
      <div class="elr-comment-body">
        <p>This article is so interesting!</p>
        <button class="elr-comment-reply">Reply</button>
      </div>
    </div>
    <div class="elr-comment elr-comment-nested">
      <div class="elr-comment-content">
        <div class="elr-comment-heading">
          <figure class="elr-comment-avatar">
            <img src="https://placekitten.com/300/200" />
          </figure>
          <div>
            <h3 class="elr-comment-author">Kate Brewster</h3>
            <p class="elr-comment-timestamp">Just Now</p>
          </div>
        </div>
        <div class="elr-comment-body">
          <p>Yes! this site always has the best articles.</p>
          <button class="elr-comment-reply">Reply</button>
        </div>
      </div>
    </div>
  </div>
</div>
```

## License

SEE LICENSE IN LICENSE.md
