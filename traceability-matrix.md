|To use:						|
|:----|
|Add/change the Req UC No ID to the ID of your requirement in both tables |
|Change the Test Case ID to one that matches your own |
|Enter an 'x' into each square where your test case tests out a specific requirement	|
|Enter the number of test cases of your requirement in row number two |
|Enter the number of test cases present in test case ID in column number two |

|Req UC No |  Details | Feature implemented by |
|:----|:----|:----|
|REQ1 UC 1.1 |  Welcome page | Liang |
|REQ1 UC 1.2 | Register manually | Liang |
|REQ1 UC 2.1 | Sign in with username and password | Liang |
|REQ1 UC 2.2 | Sign in with google (Good to have) | Liang |
|REQ1 UC 3.1 | Home page | Ambika |
|REQ1 UC 3.2 |  current location on home page and edit location | Ambika |
|REQ1 UC 3.3 |  selected location map showing pins with posts | Ambika |
|REQ1 UC 5.1 | Create a new post | Ambika |
|REQ1 UC 5.2 | Choose sketch from gallery | Ambika |
|REQ1 UC 5.3 |  Add post details and save post | Ambika |
|REQ1 UC 6.1 | Like and comment on post with saving | Vishal |
|REQ1 UC 7.1 | Delete the post | Vishal |
|REQ1 UC 8.1 | Edit profile of user | Vishal |
|REQ1 UC 9.1 | show general settings in user profile | Vishal |
|REQ1 UC 10.1 | log out from app | Vishal |
|REQ1 UC 11.1 | change location on home page and create a new post | Ambika |
|REQ1 UC 12.1 | show notifications on home page | Sifan |
|REQ1 UC 12.2 | Handle notifications Change | Sifan |


|Requirement identifiers|<small>Reqs tested</small>|REQ1 UC 1.1|REQ1 UC 1.2|REQ1 UC 2.1|REQ1 UC 2.2|REQ1 UC 3.1|REQ1 UC 3.2|REQ1 UC 3.3|REQ1 UC 5.1|REQ1 UC 5.2|REQ1 UC 5.3|REQ1 UC 6.1|REQ1 UC 7.1|REQ1 UC 8.1|REQ1 UC 9.1|REQ1 UC 10.1|REQ1 UC 11.1|REQ1 UC 12.1|REQ1 UC 12.2|
|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|:----|
|Test cases| | | | | | | | | | | | | | | | | | | | |
|<small>Tested implicitly</small>| | | | | | | | | | | | | | | | | | | | |
|[upload_test.dart](/urban_sketchers/test/screens/upload_test.dart)| | | | | | | | | x | x | x |  | | | | | x | | |
|[image_utils_test.dart](/urban_sketchers/test/utils/image_utils_test.dart)| | | | | | | | | | x |  | | | | | | | | |
|[location_utils_exp_test.dart](/urban_sketchers/test/utils/location_utils_exp_test.dart)| | | | | | | | | | | x |  | | | | | | |
|[location_utils_test.dart](/urban_sketchers/test/utils/location_utils_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[privacy_option_test.dart](/urban_sketchers/test/utils/privacy_option_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[save_post_service_test.dart](/urban_sketchers/test/utils/save_post_service_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[upload_service_test.dart](/urban_sketchers/test/utils/upload_service_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[header_test.dart](/urban_sketchers/test/widgets/header_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[progress_test.dart](/urban_sketchers/test/widgets/progress_test.dart)| | | | | | | | | | | x |  | | | | | | | |
|[custom_marker_window_test.dart](/urban_sketchers/test/screens/custom_marker_window_test.dart)| | | | | |  x| x | x | | | | | | | | | | | |
|[fake_map_controllers.dart](/urban_sketchers/test/screens/fake_map_controllers.dart)| | | | | | x | x | x | | | | | | | | | | | |
|[timeline_test.dart](/urban_sketchers/test/screens/timeline_test.dart)| | | | | | x | x | x | | | | | | | | | | | |
|[map_markers_test.dart](/urban_sketchers/test/widgets/map_markers_test.dart)| | | | | | x | x | x | | | | | | | | | | | |
|[profile_test.dart](/urban_sketchers/test/screens/profile_test.dart)| | | | | | | | | | | | | | x | x | x | | | |
|[post_model_test.dart](/urban_sketchers/test/model/post_model_test.dart)| | | | | | | | | | | | | x | | | | | | |  
|[user_model_test.dart](/urban_sketchers/test/model/user_model_test.dart)| | | | | | | | | | | | | | x | | | | | | 
|[update_profile_pic_test.dart](/urban_sketchers/test/utils/update_profile_pic_test.dart)| | | | | | | | | | | | | | x | | | | | |
|[individual_post_test.dart](/urban_sketchers/test/widgets/individual_post_test.dart)| | | | | | | | | | | | x | x | | | | | | |
|[notification_model_test.dart](/urban_sketchers/test/model/notification_model_test.dart)| | | | | | | | | | | | | | | | | | | x |
|[notification_page_test.dart](/urban_sketchers/test/screens/notification_page_test.dart)| | | | | | | | | | | | | | | | | | x |  |
|[welcome_page_test.dart](/urban_sketchers/test/screens/welcome_page_test.dart)| | x | | | | | | | | | | | | | | | | | |
|[intro_page_1_test.dart](/urban_sketchers/test/screens/intro_page_1_test.dart)| | x | | | | | | | | | | | | | | | | | |
|[intro_page_2_test.dart](/urban_sketchers/test/screens/intro_page_2_test.dart)| | x | | | | | | | | | | | | | | | | | |
|[intro_page_3_test.dart](/urban_sketchers/test/screens/intro_page_3_test.dart)| | x | | | | | | | | | | | | | | | | | |
|[intro_page_4_test.dart](/urban_sketchers/test/screens/intro_page_4_test.dart)| | x | | | | | | | | | | | | | | | | | |
|[login_page_test.dart](/urban_sketchers/test/screens/login_page_test.dart)| | | | x | | | | | | | | | | | | | | | | |
|[register_page_test.dart](/urban_sketchers/test/screens/register_page_test.dart)| | | x | | | | | | | | | | | | | | | | | |
