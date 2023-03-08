# Codechef-Notifier
a browser extension that will automatically catch the unique ID of the submissions made to the problems on Codechef and check the verdict of the judge on that submission and notify the user through desktop notification once the verdict is available

#Description
CodeChef is a platform for many aspiring coders to improve their coding skills. It is a very frequent problem with CodeChef that its servers are so overloaded that submission made to the judge takes a very long time to obtain the verdict. The coders are left with no option but to check the page repeatedly after some interval to check if the verdict is available or not.

Through this extension, we aim to remove this extra effort of checking the submission page to know the verdict of our submission. Using this extension we will automate the process of capturing the submission request and pinging the REST API of CodeChef responsible for giving the verdict repeatedly at some interval until the verdict is obtained. When the verdict is available, this extension will inform the user using desktop notifications so that the user can check the detailed status of their submission.
