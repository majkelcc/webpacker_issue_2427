### Demo rails application showing an issue with webpacker > `4.0.7` breaking hmr.
## @see https://github.com/rails/webpacker/issues/2427

This is a clean installation of rails `6.0.2.1`. Master branch is using webpacker `4.0.7` where hmr still works and https://github.com/majkelcc/webpacker_issue_2427/pulls contains the latest version of webpacker, `4.2.2` where `hmr` stops working.

Try modifying `app/javascript/styles/hello.module.scss` to see `hmr` in action.
