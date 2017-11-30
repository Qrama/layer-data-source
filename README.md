# Overview
This charm will retrieve data from an RSS-feed and is used specifically for one
of the demo-workspace of the [Tengu](https://tengu.io) platform.

# Usage

To deploy this charm:

    juju deploy activemq
    juju deploy activemq-topic <topic-name>
    juju add-relation activemq <topic-name>
    juju deploy data-source rss-feed
    juju add-relation rss-feed <topic-name>


# Contact Information

 - Sébastien Pattyn <sebastien.pattyn@tengu.io>
