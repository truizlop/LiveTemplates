# LiveTemplates

A set of live templates for IntelliJ IDEA / Android Studio

## How to install

According to Jet Brains [documentation about live templates][1], you need to copy (or clone this repo) into the following folders, depending on the Operating System you are running:

- OS X: `~/Library/Preferences/<product name><version>/templates`
- Linux: `~/.<product name><version>/config/templates`
- Windows: `<home directory>\.<product name><version>\config\templates`

## How to use

Currently, only live templates for the Android Design Support Library are published, but I intend to add more in the future and group them accordingly. I will add sections to this document as I progress.

### Design Support Library

You can type the following shortcuts in an XML layout file and press `Tab`to expand the resulting code. By default, all the widgets include all the XML attributes that appear in the [Design Support Library documentation][2]:

- **appbarlayout**

``` xml
<android.support.design.widget.AppBarLayout
    android:layout_width=""
    android:layout_height=""
    design:expanded="">
    
</android.support.design.widget.AppBarLayout>
```
- **collapsingtoolbarlayout**

``` xml
<android.support.design.widget.CollapsingToolbarLayout
    android:layout_width=""
    android:layout_height=""
    design:collapsedTitleGravity=""
    design:collapsedTitleTextAppearance=""
    design:contentScrim=""
    design:expandedTitleGravity=""
    design:expandedTitleMargin=""
    design:expandedTitleTextAppearance=""
    design:statusBarScrim=""
    design:title=""
    design:titleEnabled=""
    design:toolbarId="">
    
</android.support.design.widget.CollapsingToolbarLayout>
```
- **coordinatorlayout**

``` xml
<android.support.design.widget.CoordinatorLayout
    xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:design="http://schemas.android.com/apk/res-auto"
    android:layout_width=""
    android:layout_height="">
    
</android.support.design.widget.CoordinatorLayout>
```
- **floatingactionbutton** or **fab**

``` xml
<android.support.design.widget.FloatingActionButton
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    design:fabSize=""/>
```
- **navigationview**

``` xml
<android.support.design.widget.NavigationView
    android:layout_width="wrap_content"
    android:layout_height="match_parent"
    design:menu=""
    design:itemBackground=""
    design:itemIconTint=""
    design:itemTextAppearance=""
    design:itemTextColor=""/>
```
- **tablayout**

``` xml
<android.support.design.widget.TabLayout
    android:layout_width=""
    android:layout_height=""/>
```
- **textinputlayout**

``` xml
<android.support.design.widget.TextInputLayout
    android:layout_width=""
    android:layout_height=""
    design:counterEnabled=""
    design:errorEnabled=""
    design:hintAnimationEnabled=""
    design:hintTextAppearance="">

    <EditText
        android:layout_width=""
        android:layout_height=""
        android:hint=""/>
 </android.support.design.widget.TextInputLayout>
```

## Contribute

Feel free to clone the project and submit pull requests if you consider something is missing here. I will be glad to review and incorporate your suggestions to this repo.

## License

    Copyright 2015 Tomás Ruiz-López

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

[1]: https://www.jetbrains.com/idea/help/live-templates.html
[2]: http://developer.android.com/intl/es/reference/android/support/design/widget/package-summary.html