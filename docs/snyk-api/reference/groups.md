# Groups

{% hint style="info" %}
This document uses the REST API. For more details, see the [Authentication for API](../authentication-for-api/) page.
{% endhint %}
{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/sso_connections" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/sso_connections/{sso_id}/users" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/sso_connections/{sso_id}/users/{user_id}" method="delete" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/org_memberships" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/memberships" method="post" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/memberships" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/memberships/{membership_id}" method="patch" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/groups/{group_id}/memberships/{membership_id}" method="delete" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}
