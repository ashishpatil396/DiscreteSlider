# DiscreteSlider 

A slider that allows a user to select a value at one of the specified tickmarks

![DiscreteSlider](https://raw.githubusercontent.com/lawloretienne/DiscreteSlider/master/images/DiscreteSlider_Screenshot2.png)

## Setup

#### Gradle

`compile 'com.github.lawloretienne:discreteslider:0.0.3'`

#### Maven
```
<dependency>
    <groupId>com.github.lawloretienne</groupId>
    <artifactId>discreteslider</artifactId>
    <version>0.0.3</version>
</dependency>
```

## Sample Usage

```xml
<com.etiennelawlor.discreteslider.library.ui.DiscreteSlider
        android:layout_width="match_parent"
        android:layout_height="64dp"
        android:paddingLeft="8dp"
        android:paddingRight="8dp"
        android:layout_gravity="bottom"
        android:background="@color/grey_100"
        app:backdropFillColor="@color/grey_200"
        app:backdropStrokeColor="@color/grey_300"
        app:backdropStrokeWidth="1"
        app:horizontalBarThickness="4"
        app:tickMarkCount="6"
        app:tickMarkRadius="8"
        app:thumb="@drawable/thumb"
        app:progressDrawable="@drawable/transparent_progress_drawable"/>
```

## Notes

### XML Attributes

* **backdropFillColor** - the fill color of the slider backdrop
* **backdropStrokeColor** - the stroke color of the slider backdrop
* **backdropStrokeWidth** - the width of the stroke on the slider backdrop (in dp)
* **horizontalBarThickness** - the thickness of the horizontal bar that makes up the slider backdrop (in dp)
* **tickMarkCount** - the number of tickmarks
* **tickMarkRadius** - the radius of each tickmark (in dp)
* **thumb** - the drawable that is used as the thumb of the slider
* **progressDrawable** - the drawable that is used as the progress indicator of the slider

## Developed By

* Etienne Lawlor 
 
&nbsp;&nbsp;&nbsp;**Email** - lawloretienne@gmail.com

&nbsp;&nbsp;&nbsp;**Website** - https://medium.com/@etiennelawlor

## Projects/Apps using DiscreteSlider

Feel free to contact me to add yours to this list.

## License

```
Copyright 2016 Etienne Lawlor

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
