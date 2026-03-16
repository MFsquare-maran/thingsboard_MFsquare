<div align="center">

# IOT.MFsquare.ch

<div align="left">

## Main Color
- **Blue**: `rgb(54, 170, 207)` `#36aacf`
- **Grey1**: `rgb(48, 49, 54)` `#303136`
- **Grey2**: `rgb(66, 67, 74)` `#42434A`



---

## Instructions for Customization

### 1. Change Icons
To update the icons for the project, replace the following files:

- **For Assets**:
  - `thingsboard_MFsquare/ui-ngx/src/assets/logo_title_white.svg`
  - `thingsboard_MFsquare/ui-ngx/src/assets/logo_white.svg`

- **For Favicon**:
  - `thingsboard_MFsquare/ui-ngx/src/thingsboard.ico`

### 2. Change Index
To customize the main HTML file, modify:

- `thingsboard_MFsquare/ui-ngx/src/Index.html`

### 3. Change Color Bule & Grey

- **For Blue**
  - `ui-ngx/src/theme.scss`

- **For grey 1 & 2**
  - `ui-ngx/src/scss/constants.scss`
  

### 4. Change app Titels to IOT.MFsquare.ch

  - `ui-ngx/src/environments/environment.ts`
  - `ui-ngx/src/environments/environment.prod.ts`

### 5. Change titels in Language
  - `ui-ngx\src\assets\locale`

### 6. Change Link on img to mfsquare.ch
  - `ui-ngx\src\app\shared\models\constants.ts`

### 7. Change main background image
add image to ui-ngx\src\assets\images hintergrund.jpg
  - `\ui-ngx\src\app\modules\login\pages\login\force-two-factor-auth-login.component.sass`
  - `\ui-ngx\src\app\modules\login\pages\login\link-expired.component.sass`
  - `\ui-ngx\src\app\modules\login\pages\login\login.component.sass`
  - `\ui-ngx\src\app\modules\login\pages\login\password.component.sass`
  - `\ui-ngx\src\app\modules\login\pages\login\two-factor-auth-login.component.sass`


### 8. Change Link in dashboard-page.component.html
  - `ui-ngx\src\app\modules\home\components\dashboard-page\dashboard-page.component.html`


### 9. Change Link in app.component.ts
  - `ui-ngx\src\app\app.component.ts`


### 10. Change banner.txt
  - `thingsboard_MFsquare\application\src\main\resources\banner.txt`
  
<pre><code>
 ___ ___ _____ __  __ _____
|_ _/ _ \_   _|  \/  |  ___|__  __ _ _   _  __ _ _ __ ___
 | | | | || | | |\/| | |_ / __|/ _` | | | |/ _` | '__/ _ \
 | | |_| || |_| |  | |  _|\__ \ (_| | |_| | (_| | | |  __/
|___\___/ |_(_)_|  |_|_|  |___/\__, |\__,_|\__,_|_|  \___|
                                  |_|
 ===========================================================
 :: ${application.title} ::      ${application.formatted-version}
 ===========================================================
</code></pre>

Feel free to contribute or reach out for any questions!
</div>
