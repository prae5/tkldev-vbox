MODIFIED By Paul Rae
=========================================================
Git Repo: https://github.com/prae5/tkldev
Website: http://www.paulrae.com
=========================================================

Modified version of TurnKey Linux's TKLDev Appliance

Adds support for testing newly built ISO's in VirtualBox. 

After building iso run:

testvm build/product.iso

This will lauch iso in a virtualbox inastance. You can connect
to this virtualbox instance using RDP. 



---------------------------------------------------------

TKLDev - Appliance Development Toolchain and Build System
=========================================================

TKLDev is the mother of all TurnKey appliances. It's used to give birth
to all other appliances, including new versions of itself. It includes a
self-contained appliance development toolchain and build system that can
be used by appliance hackers to fabricate any existing or new TurnKey
appliance from `source`_.

Read the `blog post`_ announcing TKLDev for the background story and
overview.

This appliance includes all the standard features in `TurnKey Core`_,
and on top of that:

- Includes TurnKey appliance development build toolchain: `fab`_,
  `deck`_ and friends.
- Turnkey development directory structure with preconfigured CDPATH.
- Integrated caching proxy for fast and iterative development.
- Full usage and development `documentation`_.

Credentials *(passwords set at first boot)*
-------------------------------------------

-  SSH: username **root**

.. _blog post: http://www.turnkeylinux.org/blog/introducing-tkldev
.. _fab: https://github.com/turnkeylinux/fab
.. _deck: https://github.com/turnkeylinux/deck
.. _source: https://github.com/turnkeylinux-apps/
.. _TurnKey Core: http://www.turnkeylinux.org/core
.. _documentation: https://github.com/turnkeylinux-apps/tkldev/tree/master/docs
