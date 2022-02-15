## Resource naming
Resource IDs and names are written in **lowercase_underscore**.

### ID naming

#### View
| Element | Prefix |
|--|--|
|ActionBarLayout  | box_  |
|ConstraintLayout  | box_  |
|Guide  | guide_  |
|Group  | group_  |
|CoordinateLayout  | box_  |
|FrameLayout  | box_  |
|LinearLayout  | box_  |
|RelativeLayout  | box_  |
|SwipeRefreshLayout  | box_  |
|Include layout  | include_ |
|Button  |button_  |
|EditText  | edit_ |
|TextView  | label_ |
|ImageView  |image_  |
|CheckBox  | check_ |
|RadioButton  | radio_  |
|RadioGroup  | radio_group_ |
|RecyclerView  | list_ |
|NestedScrollView  | scroll_ |
|ScrollView  | scroll_  |
|SwitchButton  | switch_  |
|Toolbar  | toolbar_ |
|WebView  | web_ |
|FragmentContainerView  | fragment_container |

#### Menu
|Element  | Prefix |
|--|--|
|Menu | menu |

#### Layout
|Element  | Prefix |
|--|--|
|Activity | activity_ |
|Fragment | fragment_ |
|Dialog/DialogFragment | dialog_ |
|RecyclerView ViewHolder | item_ |
|Menu | menu_ |
|Custom view | view_ |

#### Strings
Put strings with same prefix into a same file.
Split String resource file based on the feature. 

eg) LoginFragment

 - layout: fragment_login.xml
 - menu: menu_login.xml
 - String resources: string_login.xml

|Prefx  | Description | File name |
|--|--|--|
|error_ | Error message | error_???.xml	|
|info_ |  Infomation message| info_???.xml	|
|title_ | A tilte for Activity, Fragment or Dialog.  |	|
|action_ | A button caption  |	|
