<!-- SPDX-License-Identifier: CC-BY-4.0 -->
<!-- Copyright Contributors to the Egeria project. -->

# Egeria OMRS Caching connector

Provides an OMRS repository proxy connector that has an embedded repository that can be used to cache entities and relationships. This is useful when running an adapter that uses an event mapper to poll a 3rd party technology; and then writes its content to this connector. This connector services queries by paaing them to the imbedded repository connector

See https://egeria-project.org for the main Egeria Documentation.

