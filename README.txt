Import RSS feeds
migrate-status - Lists migrations and their status.
migrate-import - Performs import operations.
migrate-rollback - Performs rollback operations.
migrate-stop - Cleanly stops a running operation.
migrate-reset-status - Sets a migration status to Idle if it's gotten stuck.
migrate-messages - Lists any messages associated with a migration import.

Example

To Import
drush migrate:import ndtv_rss_importer

To Rollback
drush migrate-rollback ndtv_rss_importer


Ensure that you have "article" content type as below
1) Title
2) Image (field_image)
3) GUID (field_guid)
4) Link (field_link)
5) Category (field_category)

Taxonomy
1) Category (category)

Required modules for this custom module
migrate_tools
migrate_plus
