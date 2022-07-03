# AlignE2eTest
.need to install：
.pip3 install selenium
.pip3 install pytest
.brew install allure(if you don't have brew,you need install brew before)
.pip3 install pytest-xdist(Multithreaded framework)
.UI E2E AUTO-Testing:chrome
.need download chromedriver:http://npm.taobao.org/mirrors/chromedriver/
.take your chromedriver path to replace the path in the AlignE2eTest-InvisalignWeb-Testcases-test_find_a_doctor.py-setup
.pytest -n 2 -m all --alluredir=allure --clean-alluredir (-n means multithreaded/-2 means start with 2 chrome once/-m means running the label for PyTest is modifiable/ --alluredir=allure means generate the original report for Allure)
.allure generate allure -o allure_html --clean(create html report)
