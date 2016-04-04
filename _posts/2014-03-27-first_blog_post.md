---
layout: post
title: "Trying out Go"
permalinl: how-i-built-this-website
---

This is where the sample text should go

### Code

Cum sociis natoque penatibus et magnis dis `code element` montes, nascetur ridiculus mus.

{% highlight matlab %}
// Example can be run directly in your JavaScript console

% This is a comment

% This is an assignment:
a = 1;

% Here is a plot command:
plot(a)

for i = 1:1:3
    scenarios_norm(:,i) = (scenarios_trial(:,i) - min(scenarios_trial(:,i))) / ( max(scenarios_trial(:,i)) - min(scenarios_trial(:,i)) );
    scenarios_norm(:,i) = scenarios_norm(:,i) .* (scl_max(i) - scl_min(i)) + scl_min(i);
end


{% endhighlight %}
