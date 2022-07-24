---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 50

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: Software Development Engineer Intern
    company: Amazon.com, Inc.
    company_url: 'https://www.amazon.com/'
    company_logo: amazon
    location: Seattle, WA, United States
    date_start: '2022-05-23'
    date_end: '2022-08-12'
    description: |2-    
        * Designed and implemented a Risk Aggregator API using Java for preventing fraud in fraud mitigation toolkit.
        * Created a plugin by AWS Lambda and API Gateway for invoking an internal back-end service and aggregated the results for upstream client.
        * Constructed the service infrastructure and pipeline by leveraging AWS CDK infrastructure eco-system.
        * Monitoring the availability and performance of the API by creating metrics, alarms, and dashboard.

  - title: Backend Developer
    company: JKOPay Co. Ltd.
    company_url: 'https://www.jkopay.com/'
    company_logo: jkopay
    location: Taipei, Taiwan
    date_start: '2020-07-01'
    date_end: '2021-06-30'
    description: |2-
        * Built e-ticketing server-side service from scratch using Java Spring Boot, MyBatis, MySQL, Docker, and ELK stack; responsible for managing project from initial documentation, database schema design, and implementation.
        * Raised 17% coupon allowance rate and gained $3000+ revenue each month in coupon service by implementing instant-payback coupon by Python Django framework, Redis Queue, Kafka, MySQL.
        * Developed a content management system by Python Django to create coupons and campaigns for marketing usage.

  - title: Software Engineer
    company: MediaTek Inc.
    company_url: 'https://www.mediatek.com/'
    company_logo: mediatek
    location: Taipei, Taiwan
    date_start: '2016-12-01'
    date_end: '2018-12-31'
    description: |2-
        * Won 2 times MStar Short Term Reward, a recognition of top 3 outstanding employees in the Division per quarter.
        * Improved video compression rate in Google AV1 c-model by 65% through implementing data compression algorithm.

design:
  columns: '3'
---
