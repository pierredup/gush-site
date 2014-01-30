---
layout: default
full_title: "Gush: Rapid workflow for project maintainers and contributors"
---
{% block hero %}
<div class="hero">
    <div class="container">
        <div class="col-sm-2 col-sm-offset-5">
            <img class="img-responsive" src="{{ site.url }}/assets/images/logo.png">
        </div>
    </div>
</div>
{% endblock %}

{% block content %}
<div class="col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
    <h1>Get it!</h1>

    <p>
        The recommended way to install <strong class="title">Gush</strong> is via composer:
    </p>

    <div class="code cli">
        <pre class="cli">$ composer global require 'cordoval/gush=dev-master'</pre>
    </div>

    <p>
        If it is the first time you globally install a dependency then make sure you include
        <strong class="title">~/.composer/vendor/bin</strong> in <strong class="title">$PATH</strong> as shown here.
    </p>

    <p>
        The other way to install <strong class="title">Gush</strong> is via a phar download.
    </p>

    <div class="code cli">
        <pre class="cli">$ curl -sS https://gushphp.org/installer | php</pre>
        <pre class="cli">$ mv gush.phar /usr/local/bin/gush</pre>
    </div>

    <p>
        After installation is done please run the <strong class="title">configure</strong> command.
    </p>

    <div class="code cli">
        <pre class="cli">$ gush configure</pre>
    </div>
</div>
{% endblock %}
