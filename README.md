# Google Plus Widget

jQuery plugin showing latest posts from Google+ profiles/pages.

#### Installation

1. Include plugin CSS file `google-plus-widget.css`, upload plugin images from `img` folder
2. Include jQuery library and plugin file `google.plus.widget.js`
3. Create container element inside your HTML document:
    ```
    <div id="google-plus-widget"></div>
    ```

4. Initialize plugin:
    ```
    $.fn.googlePlusWidget.defaults.key = 'YOUR_API_KEY'; // see `Obtaining Google Plus API key` below
    $('#google-plus-widget').googlePlusWidget({user: 'USER_OR_PAGE_ID'});
    ```

#### Obtaining Google Plus API key

1. Go to https://code.google.com/apis/console#access
2. Login and click "Create Project"
3. Under service list, click "off" button next to "Google+ API" to turn it on
4. Accept the agreement
5. From the left menu, Go to "API Access" and copy your API key
