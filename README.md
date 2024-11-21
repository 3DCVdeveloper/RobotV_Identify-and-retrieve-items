# RobotV_Identify-and-retrieve-items
Recognition and retrieval robot based on Orbbec 3D camera

cd pyorbbecsdk/pyorbbecsdk

export PYTHONPATH=$PYTHONPATH:$(pwd)/install/lib/

sudo bash ./scripts/install_udev_rules.sh

sudo udevadm control --reload-rules && sudo udevadm trigger

python3 /home/orin/pyorbbecsdk/RGBD_detection.py

python3 /home/orin/pyorbbecsdk/imgtest.py
