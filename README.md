# Comments

[![npm version](http://img.shields.io/npm/v/elr-scss-comment.svg)](https://www.npmjs.org/package/elr-scss-comment)
[![Build Status](https://github.com/elr-scss-comment/workflows/CI/badge.svg)](https://github.com/elr-scss-comment/actions?workflow=CI)
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

.comments {
  @include elr-comments;
}
```

### HTML

```html
<div class="comments">
  <div class="comment">
    <div class="comment-content">
      <div class="comment-heading">
        <figure class="comment-avatar">
          <img src="https://placekitten.com/200/200" />
        </figure>
        <div>
          <h3 class="comment-author">Joe</h3>
          <p class="comment-timestamp">10 minutes ago</p>
        </div>
      </div>
      <div class="comment-body">
        <p>This article is so interesting!</p>
        <button class="comment-reply">Reply</button>
      </div>
    </div>
    <div class="comment comment-nested">
      <div class="comment-content">
        <div class="comment-heading">
          <figure class="comment-avatar">
            <img src="https://placekitten.com/300/200" />
          </figure>
          <div>
            <h3 class="comment-author">Kate Brewster</h3>
            <p class="comment-timestamp">Just Now</p>
          </div>
        </div>
        <div class="comment-body">
          <p>Yes! this site always has the best articles.</p>
          <button class="comment-reply">Reply</button>
        </div>
      </div>
    </div>
  </div>
</div>
```

## License

SEE LICENSE IN LICENSE.md
