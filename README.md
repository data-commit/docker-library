# Deprecated Docker Images

This document lists the Docker images that have been deprecated and those scheduled for deprecation by June 2025. Please review the table below and update your dependencies accordingly.

## Deprecated Images

The following Docker images have already been deprecated:

| Image Name           | Version   | Deprecation Date |
|----------------------|-----------|------------------|
| node16               | v3.0      | June 2024        |
| python3.7            | v4.0.2    | June 2024        |

## Scheduled for Deprecation

The following Docker images are scheduled for deprecation by June 2025:

| Image Name           | Version   | Deprecation Date |
|----------------------|-----------|------------------|
| amazonlinux          | 2         | June 2025        |

Additionally, all platform images based on `amazonlinux:2` will also be deprecated. These include:

| Platform Image | Base Image       | Deprecation Date |
|----------------|------------------|------------------|
| lambda         | amazonlinux:2    | June 2025        |
| openjdk        | amazonlinux:2    | June 2025        |
| node18         | amazonlinux:2    | June 2025        |

## Action Required

Users of the deprecated images should plan to transition to the latest supported versions of these images. Continuing to use deprecated images after their deprecation date may expose your applications to security vulnerabilities and lack of support.

## Contact

For any questions or assistance with the migration process, please contact our support team at [support@example.com](mailto:support@example.com).

---

Thank you for your attention to this matter.

---

© 2024 Your Company. All rights reserved.
