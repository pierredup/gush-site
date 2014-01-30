---
layout: default
full_title: "Gush: Rapid workflow for project maintainers and contributors"
---
{% block hero %}
<div class="hero">
    <div class="container">
        <div class="col-sm-4 col-sm-offset-4">
            <img class="img-responsive" src="{{ site.url }}/assets/images/logo.png">
        </div>
    </div>
</div>
{% endblock %}
{% block content %}
<div class="col-sm-8 col-sm-offset-2 col-md-6 col-md-offset-3">
    <h1 id="enrutamiento"><span>1.</span> Instructions</h1>

    <p>
        <strong class="title">Manager Tools</strong> is an console app to help maintainers be faster.
    </p>

    <div class="code cli">
        <pre class="cli">$ curl -sS https://pilotci.com/installer | php</pre>
        <pre class="cli">$ mv manager.phar /usr/local/bin/manager</pre>
    </div>

    <h1 id="enrutamiento"><span>2.</span> Usage</h1>

    <div class="code cli">
        <pre class="cli">$ manager pr</pre>
    </div>
</div>
{% endblock %}
