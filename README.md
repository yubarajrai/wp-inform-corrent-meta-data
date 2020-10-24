# WP Inform Corrent Metadata
/**
 * Plugin Name: Inform Correct Metadata
 * Plugin URI: https://yubarajrai.name.np/plugins/inform-correct-metadata
 * Description: Inform Correct Metadata plugin is designed to enable multi user suggestion collection feature having a Product metadata choices on a post. 
 * Use comma "," to add multiple datas.
 * Version: 1.0.0
 * Author: Yubaraj Rai
 * Author URI: https://yubarajrai.name.np/
 */
 
 
 
# Uses example:

<?php 
echo do_shortcode('[inform_correct_metadata 
                    post_type="post" 
                    post_id="22" 
                    metadata_field_key="post_meta_categories" 
                    datas="Second Item, Third Item" 
                    default_data="First Item" 
                    update_on_count="10"
                  ]'); 
?>
