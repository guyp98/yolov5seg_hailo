
Native detection application
============================

Overview
--------

This example demonstrate the use of libhailort's C API as part of a detection application. The example uses the Yolov5m model, on top of the Hailo-8 device.
The application also requires opevCV.

Compiling with meson
^^^^^^^^^^^^^^^^^^^^

Run the following commands from the application's directory.

.. code-block:: sh

   CC=gcc-9 CXX=g++-9 meson build
   ninja -C build

Running the example
^^^^^^^^^^^^^^^^^^^

.. code-block::

   ./build/detection_app


