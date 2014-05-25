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
        <pre class="cli">$ composer global require 'gushphp/gush=dev-master'</pre>
    </div>

    <p>
        If it is the first time you globally install a dependency then make sure you include
        <strong class="title">~/.composer/vendor/bin</strong> in <strong class="title">$PATH</strong>
        as shown <a target="_blank" href="http://getcomposer.org/doc/03-cli.md#global">here</a>.
    </p>

    <p>
        The other way to install <strong class="title">Gush</strong> is via a phar download.
    </p>

    <div class="code cli">
        <pre class="cli">$ curl -sS http://gushphp.org/installer | php</pre>
        <pre class="cli">$ mv gush.phar /usr/local/bin/gush</pre>
    </div>

    <p>
        After installation is done please run the <strong class="title">configure</strong> command.
    </p>

    <div class="code cli">
        <pre class="cli">$ gush configure</pre>
    </div>




    <p>
    &nbsp;
    </p>
    <h6>Gush is helped by:</h6>
    <p>
    &nbsp;
    </p>
    <div style="text-align: center;">
        <a href="http://servergrove.com"><img src="http://servergrove.com/images/logos/sg160x40_b.png"/></a>
        <span>&nbsp;</span>
        <a href="https://www.versioneye.com/"><img src="https://www.versioneye.com/assets/logos/versioneye-transparent-2494db513158178b56313616264e74ab.png"/></a>
        <span>&nbsp;</span>
        <a href="http://dflydev.com/projects/gush"><img src="{{ site.url }}/assets/images/sponsors/dflydev@2x.png" width="145" height="35" /></a>
        <span>&nbsp;</span>
        <a href="http://liip.ch"><img src="{{ site.url }}/assets/images/sponsors/liip.png" width="100" height="40" /></a>
        <span>&nbsp;</span>
        <a href="http://phpperu.org"><img src="{{ site.url }}/assets/images/sponsors/phpperu.png" width="100" height="100" /></a>
        <span>&nbsp;</span>
        <a href="http://www.undergroundelephant.com"><img src="https://0.gravatar.com/avatar/c0282fc88ac5975cc27df4756c6b1166?d=https%3A%2F%2Fidenticons.github.com%2Fbf26652dcac407da985b6e2f20471318.png&r=x&s=140" width="100"/></a>
        <span>&nbsp;</span>
        <a href="http://bldr.io/"><img src="http://bldr.io/images/bldr.io.png" style="margin-left: 10px;" width="100"></a>
        <span>&nbsp;</span>
        <a href="http://www.coddict.com/"><img src="http://www.coddict.com/theme/images/logo.png" style="margin-left: 10px;" width="100"></a>
    </div>
</div>
{% endblock %}
