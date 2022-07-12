## 自定义Classname

```scss
/* body，html，这些基本元素 */
@layer base {
  body {
    @apply bg-[#141414] text-white;
  }
}

/* 自定义的classname */
@layer components {
  .headerLink {
    @apply cursor-pointer;
  }
}

```

