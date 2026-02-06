=== Justify for Paragraph Block ===
Contributors: nickdigitalprojects
Donate link: https://www.nick-digital-projects.com/justify-for-paragraph-block/
Tags: paragraph, text-alignment, justify, gutenberg, block-editor
Tested up to: 6.7
Stable tag: 1.1.0
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

Adds justify text alignment option to paragraph blocks in the Gutenberg editor.

== Description ==

This lightweight plugin enhances the WordPress Gutenberg editor by adding a justify text alignment option to paragraph blocks. Key features include:

* Simple one-click text justification
* Works seamlessly with the default Gutenberg paragraph block
* Optional typography settings for justified paragraphs
* Lightweight and performance-friendly

== Installation ==

1. Upload the 'justify-for-paragraph-block' folder to the '/wp-content/plugins/' directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Use the new justify alignment option in the paragraph block toolbar

== Typography Settings ==

From version 1.1.0, the plugin includes optional typography settings for justified paragraph blocks. These settings are available under:

Settings → Justify Paragraph → Typography Settings

Available options include:

* Justification mode
  * Standard (only `text-align: justify`)
  * Advanced (enables additional typographic enhancements)
* Automatic hyphenation (hyphens: auto)
  * Allows compatible browsers to break long words at line endings to reduce large gaps in justified text
* Adjust space between words
  * Presets: No change, Slightly larger, Slightly smaller
  * Custom value: numeric value plus unit (`em`, `px`, `rem`) for fine-grained control

Typography settings affect only justified paragraph blocks and are applied both in the editor and on the frontend.

== Frequently Asked Questions ==

= How do I use the justify alignment? =
Simply click on the justify icon in the paragraph block toolbar to align the text.

= Does this work with all themes? =
Yes, the plugin uses standard WordPress alignment classes and should work with most themes.

= Can I use this with other block types? =
Currently, this plugin is designed specifically for paragraph blocks.

== Screenshots ==

1. Justify alignment button in the paragraph block toolbar
2. Example of justified text in a paragraph block

== Changelog ==

= 1.1.0 =
* Added optional typography settings for justified paragraph blocks (hyphenation and word-spacing presets/custom)
* Applied typography settings consistently in both the block editor and the frontend
* Kept the plugin scope limited to the core Paragraph block

= 1.0.0 =
* Initial release
* Added justify alignment option for paragraph blocks

== Upgrade Notice ==

= 1.1.0 =
Recommended update. Adds optional typography settings (hyphenation and word-spacing presets/custom) for justified paragraph blocks and applies them consistently in both the editor and the frontend.

= 1.0.0 =
First public release of the plugin, adding a justify alignment option to the core Paragraph block.

== Credits ==

Developed by Nick Digital Projects.

== Recommendations ==

* Ensure you're using WordPress 5.0 or later
* PHP 7.0 or higher is recommended