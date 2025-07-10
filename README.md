# ASU Drupal Recipe

## Introduction
This recipe is intended to be used as a starting point for creating a new ASU Drupal site. It includes the following:
- A curated "ASU Modules" interface to replace the stock "Extend" modules page in Drupal. This will allow Site Administrators to limit the ability of Site Builders to enable/disable and configure only the modules that have been approved by Enterprise Technology.
- A curated "ASU Themes" interface to replace the stock "Appearance" themes page in Drupal. This will allow Site Administrators to limit the ability of Site Builders to enable/disable and configure only the themes that have been approved by Enterprise Technology.
- A mechanism for managing the governance of Drupal sites on the Acquia platform. Specifically, this will disable the SuperAdmin (user 1) account and provide a way for Site Builders to manage the majority of the site's content and management, while reserving the Administrator role for Enterprise Technology employees.
- Some base configuration settings that are common to all ASU Drupal sites.
## Requirements
### Drupal Core
- 10.3.x or higher
### Modules
- admin_toolbar
- allowed_formats
- asu_brand
- asu_config_utility
- asu_react_core
- asu_react_integration
- asu_user
- automated_cron
- big_pipe
- block
- block_content
- block_field
- breakpoint
- captcha
- cas
- ckeditor5
- components
- config
- config_update
- contact
- contextual
- crop
- current_page_crumb
- datetime
- datetime_range
- dblog
- decorative_image_widget
- devel
- devel_generate
- dynamic_page_cache
- editor
- editor_advanced_link
- editoria11y
- field_group
- field_menu
- field_states_ui
- field_ui
- file
- file_mdm
- fontawesome
- fontawesome_iconpicker_widget
- help
- history
- image
- image_widget_crop
- imagemagick
- inline_form_errors
- layout_builder
- layout_builder_restrictions
- layout_builder_usage_reports
- layout_section_classes
- linkit
- maxlength
- media
- media_library
- media_library_form_element
- menu_link_content
- menu_ui
- metatag
- node
- options
- page_cache
- paragraphs
- path
- pathauto
- redirect
- robotstxt
- schema_metatag
- search
- seckit
- select2
- shortcut
- simple_sitemap
- sophron
- taxonomy
- toolbar
- views
- views_ui
- webform
- webform_ui

## Installation
Drupal recipes are available in core starting with Drupal 10.3.x. This recipe is installed like any other recipe. See: https://www.drupal.org/project/distributions_recipes for further information. 
