Project Name
===================

This repository is ment to be used as a template for new git projects released under the Apache License 2.0 license.

##### Usage
Set your project name
~~~ sh
PROJECT_NAME=yourprojectname
~~~

...and run the following commands
~~~ sh
sudo hub clone andidev/apache-license-2.0 $PROJECT_NAME   \
cd $PROJECT_NAME                                          \
rm -r .git                                                \
git init                                                  \
git add .                                                 \
git commit -m "Added Apashe License 2.0"                  \
hub create                                                \
git push -u origin master
~~~

You need to have hub installed. You can install it with brew on OSX with the following command.
~~~ sh
brew install hub
~~~

Finally erase these instructions and replace the header with ypur project name in this the README.md file.

## License

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this work except in compliance with the License.
You may obtain a copy of the License in the LICENSE file, or at:

   http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.