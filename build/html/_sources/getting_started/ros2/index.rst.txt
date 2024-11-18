Introduction to ROS2
====================

This is an introductory-level exposure to what ROS2 is and does. For more information, check out the `main documentation <https://docs.ros.org/>`_. 
There are various ROS2 distributions, and you can use whichever distribution you want. Below is a table of ROS2 distributions:

+-------------------+-------------------+-------------------+
| Distribution      | Release Date      | End of Life       |
+===================+===================+===================+
| Jazzy Jalisco     | May 23rd, 2024    | May 2029          |
+-------------------+-------------------+-------------------+
| Iron Irwini       | May 23rd, 2023    | November 2024     |
+-------------------+-------------------+-------------------+
| Humble Hawksbill  | May 23rd, 2022    | May 2027          |
+-------------------+-------------------+-------------------+

We'll be using humble. To install humble, follow this `tutorial <https://docs.ros.org/en/humble/Installation.html>`_. 

If you don't want to install natively, you can pull the docker image:

.. code-block:: bash
   
   docker run -it ros:humble


.. toctree::
   :maxdepth: 2

   ros2_topics
   ros2_services
   ros2_actions



