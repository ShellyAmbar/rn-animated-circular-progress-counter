- A react native component of animated circular progress-bar that can use for counting up/down with animation of filling/ un-filling circle, in typescript.

- It comes with a built-in TypeScript typings and is compatible with all popular JavaScript frameworks. You can use it directly or leverage well-maintained wrapper packages that allow for a more native integration with your frameworks of choice.

# Examples:

![](./assets/videos/1.gif)
![](./assets/videos/2.gif)
![](./assets/videos/3.gif)
![](./assets/videos/4.gif)

## How to use:

```
import CircularTimer from 'rn-animated-circular-progress-counter';

  <CircularTimer
            duration={10}
            height={60}
            width={80}
            onFinish={() => {
              setShowCountDown(false);
            }}
            progressColor="pink"
            circleColor="white"
            isCountDown={true}
            animateFillProgress={true}
            intervalDuration={1000}
            strokeWidth={8}
          />
```

# CountryCodePicker Props -

| Name                 | Type           | Default               |
| -------------------- | -------------- | --------------------- |
| duration             | number         |
| width                | number         |
| height               | number         |
| viewStyle?           | ViewStyle      |
| onFinish             | () => void     |
| textStyle?           | TextStyle      |
| easingType?          | EasingFunction | EasingFunctionFactory |
| progressColor?       | string         |
| circleColor?         | string;        |
| animateFillProgress? | boolean        |
| isCountDown?         | boolean        |
| intervalDuration?    | number         |
| strokeWidth?         | number         |
