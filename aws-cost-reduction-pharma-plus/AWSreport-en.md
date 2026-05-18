
# AWS SERVICES IMPLEMENTATION REPORT

Date: May 2026

Company: Pharma Plus

Responsible: Emily Guimarães

## Introduction

This report presents the process of implementing AWS cloud services at Pharma Plus, carried out by Emily Guimarães. The goal of this project was to identify and deploy 3 AWS services with the primary objective of achieving immediate and sustained cost reduction across the company's operations.

## Project Description

The implementation was structured in 3 stages, each targeting a specific area of the business where cloud adoption could replace costly on-premise infrastructure or inefficient manual processes.

---

### Stage 1
- **Service:** Amazon EC2 with Auto Scaling
- **Focus:** Flexible, scalable compute capacity
- **Use case:** Pharma Plus runs a customer-facing ordering system and internal inventory management platform. Previously hosted on fixed on-premise servers, the infrastructure was sized for peak demand; meaning significant computing power sat idle during off-peak hours. By migrating to EC2 instances with Auto Scaling, the company now pays only for the compute it actually uses. Instances scale up automatically during busy periods (weekends, promotional campaigns) and scale back down overnight, reducing compute costs by an estimated 40% (for example).

---

### Stage 2
- **Service:** Amazon S3 (Simple Storage Service)
- **Focus:** Scalable, low-cost cloud storage
- **Use case:** Pharma Plus manages a large and growing volume of documents -- prescriptions, supplier invoices, compliance records, and product data sheets. These were previously stored on local servers requiring ongoing hardware maintenance and manual backup routines. Migrating to S3 eliminates hardware costs entirely, provides automatic redundancy across availability zones, and allows fine-grained access control by department. Storage costs dropped significantly, and the risk of data loss from hardware failure was removed.

---

### Stage 3
- **Service:** Amazon RDS (Relational Database Service)
- **Focus:** Managed relational database
- **Use case:** The company's inventory and sales database was maintained on a local server, requiring a dedicated administrator for updates, backups, and performance tuning. Moving to Amazon RDS transfers that operational burden to AWS. Automated backups, patching, and multi-AZ failover are handled by the platform, freeing the internal team to focus on higher-value work. For a pharmacy where stock accuracy is directly tied to patient safety, the reliability improvement alone justifies the migration; the cost reduction is an additional gain.

---

## Conclusion

The implementation of these three AWS services positions Pharma Plus to operate with a leaner, more resilient infrastructure. Compute costs are now tied to actual usage, storage scales without capital expenditure, and the database runs with enterprise-grade reliability without a dedicated operations team. It is recommended that Pharma Plus continues to evaluate further AWS services; particularly AWS Lambda for automating routine operational tasks -- as the business grows.

## Attachments

- No attachments applicable for this implementation stage.
- Information based on module 5, Notions of Cloud Computing. 

---

*Project lead: Emily Guimarães*
