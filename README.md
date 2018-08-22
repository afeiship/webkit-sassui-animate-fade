# webkit-sassui-animate-fade
> Webkit animate fade sass

## example:
```scss
.webkit-sassui-animate-fade{
  @keyframes fade-in {
    to {
      background: rgba(#000, 0.8);
    }
  }
  @keyframes fade-out {
    from {
      background: rgba(#000, 0.8);
    }
    to {
      background: rgba(#000, 0);
    }
  }

  &.visible-true,
  &[data-visible=true] {
    background: rgba(#000, 0);
    animation: fade-in 0.3s ease-in forwards;
  }

  &,
  &.visible-false,
  &[data-visible=false] {
    animation: fade-out 0.3s ease-in forwards;
  }
}
```

## usage:
+ https://afeiship.github.io/webkit-sassui-animate-fade/

## resources:
+ https://github.com/afeiship/generator-webkit-sassui
