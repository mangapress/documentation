---
---
## Changelog
### 3.0
#### 3.0.0
   * Removed child themes
   * Added sorting options for Comic Archive Page
   * Added comic archive calendar template
   * Added comic archive gallery template
   * Removed insert navigation option

### 2.9
#### 2.9.3
   * Spanish language updates to embedded themes.

#### 2.9.2
   * Added support for Jetpack Publicize feature.

#### 2.9.1
   * Corrects an issue where Comic posts were not getting assigned to a default Series taxonomy on save.
   * Corrects Comic post 404 error/Missing Comic post issue.
   * Corrects appearance of comic navigation on Latest Comic page

#### 2.9.0
   * Updated navigation CSS
   * Removed "Order By" Option. Now defaults to date.
   * Removed "Use Theme Template" options. Now defaults to using theme templates.
   * Added contextual help tabs
   * Added Calendar template tag for comics
   * Added filter for changing Comic post-type front slug (defaults to `comic`)
   * Fixed missing "No comics" message for Latest Comic page.
   * Corrected issue with Comic Post terms getting updated on post-save.
   * Updated Spanish Language files.
   * Updated child-themes to handle styling for Comic Calendar widget
   * Corrected issues in comic navigation when Group Comics/Group By Parent options are used.
   * Added Manga+Press-specific version of WordPress calendar widget
   * Updated Comic date permalink structure
   * Updated and fixed loading of Spanish Language files
   * Adjusted template hierarchy for Latest Comic and Comic Archive pages to use WordPress' defaults (page-{slug-name}.php and {custom-page-template}.php)
   * Brought default Single Comic template in line with default Latest Comic and Comic Archive template handling
      * Incidently corrects an issue where a Single Comic post might not display correctly due to markup being incompatible with a user's selected theme.

### 2.8
#### 2.8.3
   * Correcting blank issue when "Use Theme Template" is selected when used with third-party themes

#### 2.8.2
   * Correcting Latest Comic template error when Latest Comic is used as front page.

#### 2.8.1.1
   * Correcting problem with undefined function error appearing when Latest Comic template in TwentyFourteen theme is used


#### 2.8.1
   * Corrected E_STRICT notice on plugin activation
   * Updated font icons

#### 2.8
   * Added bundled child-themes for TwentyEleven, TwentyTwelve, TwentyThirteen, and TwentyFourteen
   * Updated admin interface to fit WordPress 3.8
   * Corrected 404 issues for custom post-type after activation
   * Adjusted template stack for single comics
   * Added new Media Library popup (eliminating legacy ThickBox dependency)
   * Code review and cleanup
   * Removed legacy options (Comic Banner)

### 2.7
#### 2.7.5
   * Fixed 404 when visiting comic pages after update (ported from upcoming 2.8 release)
   * Fixed undefined index errors caused by checkboxes when settings page is updated
   * Tested works with WordPress 3.8

#### 2.7.4
   * Fixed SQL bugs relating to "Group By Category" option

#### 2.7.3
   * Added "Group By Category" parent option

#### 2.7.2
   * Added Spanish Language support.
   * Fixed issues with comic navigation.
   * Addressing query-usage on Latest Comic page.

#### 2.7.1
   * Fixed undefined index notices (WP_DEBUG turned on)

#### 2.7 RC 1
   * Moved partial templates to sub-directory inside templates.
   * Corrected issues in comic-specific conditional functions.
   * Changed Ajax hooks to be admin-specific.

#### 2.7 Beta 3
   * Updates processing for templates.

#### 2.7 Beta 2
   * Fixes a problem with the Manga+Press Options page. A path issue in the framework may prevent option fields from displaying properly.