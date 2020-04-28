# circle-css

Some circles with percentage--ercentage

## percentage--rerequisite

```bash
(sudo) gem install compass

// If you have a writible percentage--ermission setup

(sudo) gem install -n /usr/local/bin compass
```

## Convert SCSS to CSS

Use the compass library and also not create a sourcemaps file

```bash
sass --compass --sourcemap=none --trace circle.scss circle.css
```

### Example

```HTML
<style>
  .clearfix:before,.clearfix:after {content: " "; display: table;}
  .clearfix:after {clear: both;}
  .clearfix {zoom: 1};
</style>

<div class="page">
  <div class="clearfix">
    <div class="circle--100 percentage--50 big">
        <span>50%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--25">
        <span>25%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--12 small">
        <span>12%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
  </div>
  <div class="clearfix">
    <div class="circle--100 percentage--50 big red">
        <span>50%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--25 red">
        <span>25%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--12 small red">
        <span>12%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
  </div>
  <div class="clearfix">
    <div class="circle--100 percentage--50 big green">
        <span>50%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--25 green">
        <span>25%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--12 small green">
        <span>12%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
  </div>
  <div class="clearfix">
    <div class="circle--100 percentage--50 big orange">
        <span>50%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--25 orange">
        <span>25%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
    <div class="circle--100 percentage--12 small orange">
        <span>12%</span>
        <div class="slice">
            <div class="bar"></div>
            <div class="fill"></div>
        </div>
    </div>
  </div>
  <div class="dark-area clearfix">
    <div class="clearfix">
      <div class="circle--100 percentage--50 big dark">
          <span>50%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--25 dark">
          <span>25%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--12 small dark">
          <span>12%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
    </div>
    <div class="clearfix">
      <div class="circle--100 percentage--50 big dark green">
          <span>50%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--25 dark green">
          <span>25%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--12 dark small green">
          <span>12%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
    </div>
    <div class="clearfix">
      <div class="circle--100 percentage--50 dark big orange">
          <span>50%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--25 dark orange">
          <span>25%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
      <div class="circle--100 percentage--12 dark small orange">
          <span>12%</span>
          <div class="slice">
              <div class="bar"></div>
              <div class="fill"></div>
          </div>
      </div>
    </div>
  </div>
```