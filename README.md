# Banners for beta-releases

Include links to the public repository of your project to simplify the potential bug discoveries.

Using `position: fixed` as this is currently supported by all evergreen browsers

example left-positioning:

```html
<div class="beta-wrapper beta-left ">
  <div class="beta beta-blue  ">
    <a class="beta-link " href="//github.com/########">
      <span class="beta-text">
        This is a Beta release.
      </span>
      <span class="beta-text">
        For any issues please raise a ticket on GitHub
      </span>
    </a>
  </div>
</div>
```

For the other 3 positions please check the `beta.html` file
