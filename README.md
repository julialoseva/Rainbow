## At a Glance

`Rainbow` gives you set of colors listed in [Google Material](https://material.io/design/color/the-color-system.html#color-theme-creation) guidelines. With `Rainbow` you can pick a color from ready collection instead of copying hexademical values into your `colors.xml`.

## How to Get Started

Add `jitpack.io` repository to your project:

```javascript
allprojects {
 repositories {
    jcenter()
    maven { url "https://jitpack.io" }
 }
}
```

Then add `Rainbow` to dependencies list:

```javascript
dependencies {
    compile 'com.github.julialoseva:Rainbow:1.0.5'
}
```

## Requirements

* Android SDK 15 and later
* Android Studio 3.0 and later
* Java 7 and later

## Usage

`Rainbow` provides you with full list of [Material colors](https://material.io/design/color/the-color-system.html#color-theme-creation). Simply type `@color/color<Name><Level>` to get a color:

```xml
<TextView
          android:text="This is a text view."
          android:background="@color/colorGray900"
          android:textColor="@color/colorPink300"
          />
```

## License

`Rainbow` is available under the MIT license. See the [LICENSE](./LICENSE) file for more info.
