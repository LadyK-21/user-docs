# SBOM

{% hint style="info" %}
This document uses the REST API. For more details, see the [Authentication for API](../authentication-for-api/) page.
{% endhint %}
{% swagger src="../../.gitbook/assets/rest-spec.json" path="/orgs/{org_id}/sbom_tests" method="post" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/orgs/{org_id}/sbom_tests/{job_id}" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/orgs/{org_id}/sbom_tests/{job_id}/results" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}

{% swagger src="../../.gitbook/assets/rest-spec.json" path="/orgs/{org_id}/projects/{project_id}/sbom" method="get" %}
[spec.yaml](../../.gitbook/assets/rest-spec.json)
{% endswagger %}
