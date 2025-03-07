.. _samples:

Samples
#######

The |NCS| provides samples that specifically target Nordic Semiconductor devices and show how to implement typical use cases with Nordic Semiconductor libraries and drivers.

Samples showcase a single feature or library, while :ref:`applications` include a variety of libraries to implement a specific use case.

Zephyr also provides a variety of application samples and demos.
Documentation for those is available in Zephyr's :ref:`zephyr:samples-and-demos` section.
For very simple samples, see the :ref:`zephyr:basic-sample`.
Those samples are a good starting point for understanding how to put together your own application.

.. note::
   All samples in the |NCS| are configured to perform a system reset if a fatal error occurs.
   This behavior is different from how fatal errors are handled in the Zephyr samples.
   You can change the default behavior by updating the configuration option :kconfig:`CONFIG_RESET_ON_FATAL_ERROR`.

.. toctree::
   :maxdepth: 1
   :glob:
   :caption: Subpages:

   samples/samples_bl.rst
   samples/samples_crypto.rst
   samples/samples_edge.rst
   samples/samples_matter.rst
   samples/samples_nfc.rst
   samples/samples_nrf5340.rst
   samples/samples_nrf9160.rst
   samples/samples_thread.rst
   samples/samples_zigbee.rst
   samples/samples_other.rst
