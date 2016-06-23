---
layout: doc
permalink: /docs/ui-toolkit/dividers
title: Dividers
---

# Dividers

Dividers are components used to add space or any other separator between other components.

## Divider
![alt text]({{ site.baseurl }}/img/ui-toolkit/divider@2x.png "Divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider />
```

## Line divider
![alt text]({{ site.baseurl }}/img/ui-toolkit/line_divider@2x.png "Line divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider styleName="line" />
```

## Section divider
Section dividers are usually used in lists, to separate groups of similar list items, for example to group contacts by the first letter of their name. ListView will automatically style all dividers added to it.

![alt text]({{ site.baseurl }}/img/ui-toolkit/section_divider@2x.png "Section divider"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider />
```

## Section divider + Label
![alt text]({{ site.baseurl }}/img/ui-toolkit/section_divider_+_label@2x.png "Section divider + Label"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider>
  <Caption>INFORMATION</Caption>
</Divider>
```

## Section divider + Label + Caption
![alt text]({{ site.baseurl }}/img/ui-toolkit/section_divider_+_label_+_caption@2x.png "Section divider + Label + Caption"){:.docs-component-image}

#### JSX Declaration
```JSX
<Divider>
  <View styleName="horizontal">
    <Caption styleName="flexible">PRODUCT NAME</Caption>
    <Caption>PRICE</Caption>
  </View>
</Divider>
```

#### Style
* **flexible**: makes a component flexible (stretchable)