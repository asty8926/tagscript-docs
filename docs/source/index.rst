Home
====

.. attention::

    This is not affiliated in any way with Botlabs or Carl-bot.

.. attention::

    Really would like to thank `readthedocs.org <https://readthedocs.org>`_ for making this possible, thank you!

This is an unofficial guide to Carl-bot's tagscript, started by `_Leg3ndary#5759 <https://discordapp.com/users/360061101477724170/>`_, you may view all contributors :doc:`here. </contributing>`


.. note::
    
    All of this documentation contains custom tagscript syntax highlighting through ansi!

    .. ansi-block::

        [1;31m{[1;32m=[1;34m([1;37mL1[1;34m)[1;34m:[1;31m{[1;32mlower[1;34m:[1;31m{[1;37m1[1;31m}[1;31m}[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37mA2[1;31m+[1;34m)[1;34m:[1;31m{[1;32mreplace[1;34m([1;35m|[1;33m,[1;37m - [1;34m)[1;34m:[1;31m{[1;32margs[1;34m([1;37m2[1;31m+[1;34m)[1;31m}[1;31m}[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37merror[1;34m)[1;34m:[1;37mYou must follow the `afk` command with either `on` or `off`.[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37mon[1;34m)[1;34m:[1;37madd[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37moff[1;34m)[1;34m:[1;33mdel[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37mtemplate[1;34m)[1;34m:[1;37mc[1;34m:[1;37mar [1;31m{[1;31m{[1;37mL1[1;31m}[1;31m}[1;37m [1;31m{[1;32muser[1;34m([1;35mid[1;34m)[1;31m}[1;35m>[1;31m{[1;33mif[1;34m([1;31m{[1;37mL1[1;31m}[1;35m==[1;37mon[1;34m)[1;34m:[1;37m [1;31m{[1;33mif[1;34m([1;31m{[1;32mlist[1;34m([1;37m0[1;34m)[1;34m:[1;31m{[1;32mjoin[1;34m([1;33m,[1;34m)[1;34m:[1;31m{[1;37mA2[1;31m+[1;31m}[1;31m}[1;31m}[1;35m!=[1;34m)[1;34m:[1;31m{[1;37mA2[1;31m+[1;31m}[1;35m|[1;31m{[1;32mreplace[1;34m([1;35m|[1;33m,[1;37m - [1;34m)[1;34m:[1;31m{[1;32muser[1;31m}[1;31m}[1;37m is afk right [4;36mnow[1;33m,[1;37m send them a PM or wait for them to return.[1;31m}[1;31m}[1;31m}[1;37m
        [1;31m{[1;32m=[1;34m([1;37msel[1;34m)[1;34m:[1;31m{[1;33mif[1;34m([1;31m{[1;32mcontains[1;34m([1;31m{[1;37mL1[1;31m}[1;34m)[1;34m:[1;37mon off[1;31m}[1;35m==[4;36mfalse[1;34m)[1;34m:[1;37merror[1;35m|[1;31m{[1;37mtemplate[1;31m}[1;31m}[1;31m}[1;37m
        [1;31m{[1;33moverride[1;31m}[1;31m{[1;31m{[1;37msel[1;31m}[1;31m}[1;37m

        - Raffael#1372's AFK Tag

.. tip::

    If you just want a quick refresher on blocks, this tag will show you everything you need to know: `?tse <block> <https://carl.gg/t/204246>`_

.. note::

    This documentation is still under development.

.. toctree::
    :caption: Info
    :maxdepth: 0
    :hidden:

    contributing
    credits

.. toctree::
    :caption: Frequently Asked Questions
    :maxdepth: 5
    :hidden:

    FAQ/tag_limits

.. toctree::
    :caption: Getting Started
    :maxdepth: 5
    :hidden:

    GettingStarted/creating_tags

.. toctree::
    :caption: Block Reference
    :maxdepth: 5
    :hidden:

    BlockReference/anatomy
    BlockReference/default
    BlockReference/discord
    BlockReference/meta
    BlockReference/commands
    BlockReference/control
    BlockReference/datastorage
    BlockReference/parsing

.. toctree::
    :caption: Advanced Concepts
    :maxdepth: 5
    :hidden:

    AdvancedConcepts/tag_saving

.. toctree::
    :caption: Custom Tags
    :maxdepth: 2
    :hidden:

    CustomTags/_Leg3ndary

.. raw:: html

    <meta property="og:title" content="Tagscript Unofficial Docs" />
    <meta property="og:type" content="Site Content" />
    <meta property="og:url" content="https://tagscript-docs.readthedocs.io/en/latest/index.html" />
    <meta property="og:site_name" content="By _Leg3ndary#5759">
    <meta property="og:image" content="https://i.imgur.com/AcQAnss.png" />
    <meta property="og:description" content="The unofficial but better docs for Carl-bots Tagscript, not affiliated with Botlabs or Carl-bot" />
    <meta name="theme-color" content="#2980B9">