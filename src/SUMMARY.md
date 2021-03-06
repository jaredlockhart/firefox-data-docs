[Firefox Data Documentation](introduction.md)
* [Getting Started](concepts/getting_started.md)
  * [Gaining Access](concepts/gaining_access.md)
  * [Analysis Quick Start](concepts/analysis_intro.md)
  * [Intro to Metrics](metrics/intro.md)
  * [Common Analysis Gotchas](concepts/analysis_gotchas.md)
  * [Choosing a Desktop Dataset](concepts/choosing_a_dataset.md)
  * [Choosing a Mobile Dataset](concepts/choosing_a_dataset_mobile.md)
  * [Intro to STMO](tools/stmo.md)
  * [Optimizing Queries](concepts/sql_optimization.md)
  * [Terminology](concepts/terminology.md)
  * [Getting Help](concepts/getting_help.md)
  * [Reporting a problem](concepts/reporting_a_problem.md)
* [Tools](tools/index.md)
  * [Project Glossary](tools/projects.md)
  * [Guiding Principles for Data Infrastructure](tools/guiding_principles.md)
  * [Overview of Mozilla's Data Pipeline](concepts/pipeline/gcp_data_pipeline.md)
    * [HTTP Edge Server Specification](concepts/pipeline/http_edge_spec.md)
    * [Event Pipeline Detail](concepts/pipeline/event_pipeline.md)
    * [Schemas](concepts/pipeline/schemas.md)
  * [Analysis Interfaces](tools/interfaces.md)
  * [Custom analysis with Spark](tools/spark.md)
  * [SQL Style Guide](concepts/sql_style.md)
  * [Glean overview](concepts/glean/glean.md)
    * [Accessing Glean data](concepts/glean/accessing_glean_data.md)
    * [Glean Debug ping viewer](concepts/glean/debug_ping_view.md)
  * [Growth & Usage Dashboard (GUD)](tools/gud.md)
* [Metrics](metrics/index.md)
  * [Definitions](metrics/definitions.md)
    * [Metrics](metrics/metrics.md)
    * [Usage Criteria](metrics/usage.md)
    * [Slicing Dimensions](metrics/dimensions.md)
  * [Metrics Standardization and Policy](metrics/policy.md)
* [Analysis cookbooks](cookbooks/index.md)
    * [Accessing and working with BigQuery](cookbooks/bigquery.md)
        * [Accessing BigQuery](cookbooks/bigquery/access.md)
        * [Writing BigQuery Queries](cookbooks/bigquery/querying.md)
        * [Optimizing BigQuery Queries](cookbooks/bigquery/optimization.md)
  * [Dataset Specific](cookbooks/dataset_specific.md)
    * [Working with Normandy events](cookbooks/normandy_events.md)
    * [Working with Crash Pings](cookbooks/crash_pings.md)
  * [Real-time](cookbooks/realtime.md)
    * [Seeing Your Own Pings](cookbooks/view_pings_cep.md)
  * [Metrics](cookbooks/metrics.md)
    * [Daily Active Users (DAU and MAU)](cookbooks/dau.md)
    * [Active DAU (aDAU)](cookbooks/active_dau.md)
    * [Retention](cookbooks/retention.md)
* [Operational cookbooks](cookbooks/index.md)
    * [Creating a new Data Project on Google Cloud Platform](cookbooks/gcp-projects.md)
    * [Scheduling BigQuery Queries in Airflow](cookbooks/bigquery-airflow.md)
    * [Building and Deploying Containers to GCR with CircleCI](cookbooks/deploying-containers.md)
    * [Publishing Datasets](public_data/publishing_datasets.md)
* [Sending telemetry](datasets/new_data.md)
  * [Implementing Experiments](cookbooks/client_guidelines.md)
  * [Sending Events](cookbooks/events_best_practices.md)
  * [Sending a Custom Ping](cookbooks/new_ping.md)
* [Public data](public_data/index.md)

---

* [Dataset Reference](datasets/reference.md)
  * [Pings](datasets/pings.md)
  * [Derived Datasets](datasets/derived.md)
    * [Active Profiles](datasets/active_profiles.md)
    * [Addons](datasets/batch_view/addons/reference.md)
    * [Addons Daily](datasets/other/addons_daily/reference.md)
    * [AS aggregates](datasets/other/asn_aggregates/reference.md)
    * [Attitudes Daily](datasets/other/attitudes_daily/reference.md)
    * [Clients Daily](datasets/batch_view/clients_daily/reference.md)
    * [Clients Last Seen](datasets/bigquery/clients_last_seen/reference.md)
    * [Events](datasets/batch_view/events/reference.md)
    * [Exact MAU](datasets/bigquery/exact_mau/reference.md)
    * [First Shutdown Summary](datasets/batch_view/first_shutdown_summary/reference.md)
    * [Main Summary](datasets/batch_view/main_summary/reference.md)
    * [New Profile](datasets/obsolete/new_profile/reference.md)
    * [Socorro Crash Reports](datasets/other/socorro_crash/reference.md)
    * [SSL Ratios (public)](datasets/other/ssl/reference.md)
    * [Telemetry Aggregates](datasets/batch_view/telemetry_aggregates/reference.md)
    * [Update](datasets/batch_view/update/reference.md)
  * [Experimental Datasets](tools/experiments.md)
    * [Accessing Heartbeat data](datasets/heartbeat.md)
    * [Accessing Shield Study data](datasets/shield.md)
    * [Dynamic telemetry](datasets/dynamic_telemetry.md)
  * [Search Datasets](datasets/search.md)
    * [Search Aggregates](datasets/search/search_aggregates/reference.md)
    * [Search Clients Daily](datasets/search/search_clients_daily/reference.md)
    * [Search Clients Last Seen](datasets/search/search_clients_last_seen/reference.md)
  * [Other Datasets](datasets/other.md)
    * [hgpush](datasets/other/hgpush/reference.md)
    * [Stub installer ping](datasets/other/stub_installer/reference.md)
    * [Activity Stream](datasets/other/activity-stream/reference.md)
    * [bmobugs](datasets/other/bmobugs/reference.md)
  * [Firefox Accounts Datasets](datasets/fxa.md)
    * [Firefox Account Attribution](datasets/fxa_metrics/attribution.md)
    * [Firefox Account Funnel Metrics](datasets/fxa_metrics/funnels.md)
    * [Firefox Account Email Metrics](datasets/fxa_metrics/emails.md)
  * [Static Datasets](datasets/static.md)
    * [Normalized OS Names And Versions](datasets/static/normalized_os.md)

---

* [Telemetry Behavior Reference](concepts/index.md)
    * [History of Telemetry](concepts/history.md)
    * [Profile Behavior](concepts/profile/index.md)
        * [Profile Creation](concepts/profile/profile_creation.md)
        * [Real World Usage](concepts/profile/realworldusage.md)
        * [Profile History](concepts/profile/profilehistory.md)
    * [Channel Behavior](concepts/channels/index.md)
        * [Channel Normalization and Querying](concepts/channels/channel_normalization.md)
    * [Census metrics](concepts/censuses.md)
    * [Engagement metrics](concepts/engagement.md)
    * [Segments](concepts/segments.md)
    * [Sampling](concepts/sample_id.md)

---

* [Historical Reference](historical/index.md)
  * [Previous AWS Pipeline Overview](concepts/pipeline/data_pipeline.md)
  * [In-depth AWS Data Pipeline Detail](concepts/pipeline/data_pipeline_detail.md)
  * [Obsolete Datasets](datasets/obsolete.md)
    * [Churn](datasets/obsolete/churn/reference.md)
    * [Client Count](datasets/obsolete/client_count/reference.md)
    * [Client Count Daily](datasets/obsolete/client_count_daily/reference.md)
    * [Crash Aggregates](datasets/obsolete/crash_aggregates/reference.md)
    * [Crash Summary](datasets/obsolete/crash_summary/reference.md)
    * [Error Aggregates](datasets/obsolete/error_aggregates/reference.md)
    * [Heavy Users](datasets/obsolete/heavy_users/reference.md)
    * [Longitudinal](datasets/obsolete/longitudinal/reference.md)
    * [Retention](datasets/obsolete/retention/reference.md)
    * [Sync Summary](datasets/obsolete/sync_summary/reference.md)

---

* [About this Documentation](meta/index.md)
  * [Contributing](meta/contributing.md)
  * [Structure](meta/structure.md)
