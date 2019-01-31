### odometer
---
https://github.com/HubSpot/odometer

```js
window.odometerOptions = {
  auto: false,
  selector: '.my-numbers',
  format: '(,ddd).dd',
  duration: 3000,
  theme: 'car',
  animation: 'count'
};

var el = document.querySelector('.some-element');
od = new Odometer({
  el: el,
  value: 333555,
  format: '',
  theme: 'digital'
});
od.update(555)
el.innerHTML = 555
```

```
npm install
grunt
grunt watch
```

```
<link rel="stylesheet" href="odometer-theme-car.css" />
<script src="odometer.js">
element.innerHTML = 123
$('.odometer').html(123)
</script>
```

