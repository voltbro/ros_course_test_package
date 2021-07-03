Для установки пакета, необходимо склонировать репозиторий в вашу папку `catkin_ws/src`

```bash
cd ~/catkin_ws/src
git clone https://github.com/voltbro/ros_course_test_package
```

Далее необходимо запустить процесс сборки пакета

```bash
cd ~/catkin_ws
catkin_make --pkg=ros_course_test_package
```
