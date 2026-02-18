# conditional-dropdown-hivepress
Conditional drodowns for hivepress, managable in admin 
=== HivePress Conditional Fields ===
Contributors: hivepress forum community
Tags: hivepress, conditional fields, parent child dropdown, car make model, country city
Requires at least: 5.0
Tested up to: 6.4
Requires PHP: 7.4
Stable tag: 1.0.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds conditional parent-child dropdown fields to HivePress listings with CSV import support.

== Description ==

HivePress Conditional Fields is a powerful extension that allows you to create unlimited conditional (parent-child) dropdown field pairs for your HivePress listings.

**Features:**

* **Unlimited Field Pairs** - Create as many conditional field pairs as needed (car_make → car_model, country → city, etc.)
* **Strict Dependency** - Child options dynamically update based on parent selection
* **CSV Import/Export** - Easy bulk data management with simple CSV format
* **Search & Filter** - Enable/disable search functionality for large datasets
* **Display Areas** - Configure where fields appear (page/block, primary/secondary/ternary)
* **Performance Optimized** - AJAX loading for large datasets with configurable threshold
* **Admin Backend** - Full admin interface for managing field pairs and data
* **Frontend Integration** - Seamless integration with listing submit/edit forms

== Installation ==

1. Upload the plugin files to `/wp-content/plugins/hivepress-conditional-fields/`
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Go to 'Conditional Fields' in the admin menu to configure

== Usage ==

1. **Create Field Pair**: Go to Conditional Fields > Field Pairs and create a new pair
2. **Add Data**: Go to Manage Data or import via CSV
3. **Configure Display**: Set display areas and search/filter options
4. **Test**: Create a new listing to see the conditional fields in action

== CSV Format ==

Simple two-column format:
```
parent_value,child_value
Toyota,Camry
Toyota,Corolla
Honda,Accord
```

== Changelog ==

= 1.0.0 =
* Initial release
