Animazione css del battito
---

Quando viene aggiunta la classe *.beat* ad un elemento html questo inizia a pulsare. 

```
@keyframes heartbeat {
  7.46% {
    opacity: 1;
  }
  14.17% {
    opacity:0;
  }
  25.36% {
    opacity:1;
  }
  100% {
    opacity:0;
  }
}

.beat{
  animation: heartbeat 2000ms ease-in-out 0s  normal;
}
```
