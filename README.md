> [!NOTE]
> This project is part of the [DevOpsTheHardWay][DevOpsTheHardWay] course. 


# The Polybot Service: Python Project [![][autotest_badge]][autotest_workflow]

## Background

This project is a simple python application backend which applies filters to images sent by users to a Telegram bot. 

Here is a short demonstration:

![app demo](.github/python_project_demo.gif)


### Filters for you to try-out

The PolyBot service allows you to enjoy a few different filters for your image - processing :
* **CONCAT** - Add this caption for a couple of images sent to the bot in order to concatenate them to a single image.
* **SALT AND PEPPER** - Add this caption to your image in order to color certain pixels black and white, randomally.
* **ROTATE** - Add this caption to your image in order to rotate your image in a clockwise manner.  
You could also specify number of rotations in order to rotate your image more than once. 
* **SEGMENT** - Add this caption to your image in order to partition the image into regions where the pixels have similar attributes, so the image is represented in a more simplified manner, and so we can then identify objects and boundaries more easily. 
* **BLUR** - Add this caption to your image in order to blur your image.
* **CONTOUR** - Add this caption to your image in order to add a contour effect to the image.  
This is done by calculating the differences between neighbor pixels along each row of the image matrix

### Notes
In order to use the PolyBot service, you need to attach images from your telegram desktop app.


## Good Luck and ENJOY !

[DevOpsTheHardWay]: https://github.com/exit-zero-academy/DevOpsTheHardWay
[autotest_badge]: ../../actions/workflows/project_auto_testing.yaml/badge.svg?event=push
[autotest_workflow]: ../../actions/workflows/project_auto_testing.yaml/
[fork_github]: https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository
[clone_pycharm]: https://www.jetbrains.com/help/pycharm/set-up-a-git-repository.html#clone-repo
[github_actions]: ../../actions

[python_project_demo]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_demo.gif
[python_project_pixel]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_pixel.gif
[python_project_imagematrix]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_imagematrix.png
[python_project_pythonimage]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_pythonimage.png
[python_project_webhook1]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_webhook1.png
[python_project_webhook2]: https://exit-zero-academy.github.io/DevOpsTheHardWayAssets/img/python_project_webhook2.png


