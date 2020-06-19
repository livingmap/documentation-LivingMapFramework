Security
========

.. contents::
    :depth: 2
    :local:

Overview
--------

The *Living Map Framework* undergoes stringent security reviews on a regular basis. These reviews are undertaken by an external assessment organisation, and encapsulates analysis of the SDK code, the Living Map APIs and backend services it accesses, and the infrastructure they run on.

As the *Living Map Framework* consists of a number of SDKs, to be integrated within an external application, there are a number of security concerns that should be taken into consideration; these are outlined in the section below.


Considerations
--------------

The following security concerns should be considered when integrating any *Living Map Framework* SDK into an application. For further clarification, or assistance in mitigating security concerns, contact the :ref:`doc_support-desk`.


Running on Jail-broken / Rooted Devices
+++++++++++++++++++++++++++++++++++++++

Jail-breaking, or device rooting, is a procedure by which an iOS or Android device is modified so that the user can take full control of the device. In doing so this puts the device and its applications at risk of tampering, for example:

* it allows for reverse engineering and debugging of running code,
* it allows full access to the device's file system,
* it allows for unsigned code fragments or full applications to run with elevated privileges.

There is a fair argument that running of an application on a jail-broken or rooted device may be a valid use case. As such, the *Living Map Framework* will **not** prevent itself from running on these devices.

Therefore, it is advised that where there is no requirement to run an application on a jail-broken or rooted device, then doing so should be prevented by whatever means are available through the respectful target platforms.