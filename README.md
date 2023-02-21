# WP-CPT-Line-Break
Add a line break every 5 sentences to a custom post type on WordPress


Just change 'custom_post_type' to your custom post type. 

You can also add a second <br /> if you need to by changing 
$new_content .= '<br />';
to 
$new_content .= '<br /><br />';

To increase or decrease number of sentences just edit the 5 on this line
if ($i % 5 == 0) {
