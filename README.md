# Awesome S3

A curated list of projects, tools, and resources related to S3-compatible object storage.

Projects released under OSI-approved open-source licenses are preferred, but projects with proprietary or commercial licenses are also welcome.

Contributions to this list are welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md).

## Table of contents

- [Storage clients & tools](#storage-clients--tools) `9`
- [Proxies & gateways](#proxies--gateways) `6`
- [Backup, recovery & synchronization](#backup-recovery--synchronization) `4`
- [Development & integrations](#development--integrations) `6`
- [Security & testing](#security--testing) `5`
- [Automation & deployment](#automation--deployment) `5`

## Storage clients & tools

[mickael-kerjean/filestash](https://github.com/mickael-kerjean/filestash) `AGPL-3.0` - Universal File Management Platform (for humans and agents).

[kahing/goofys](https://github.com/kahing/goofys) `Apache-2.0` - A high-performance, POSIX-ish Amazon S3 file system written in Go.

[Kuingsmile/PicList](https://github.com/Kuingsmile/PicList) `MIT` - An image upload and manage tool, base on PicGo

[Forceu/Gokapi](https://github.com/Forceu/Gokapi) `AGPL-3.0` - Lightweight selfhosted Firefox Send alternative without public upload. AWS S3 supported.

[cloudlena/s3manager](https://github.com/cloudlena/s3manager) `Apache-2.0` - A Web GUI for your S3 buckets.

[lusingander/stu](https://github.com/lusingander/stu) `MIT` - TUI explorer application for Amazon S3 (AWS S3).

[dimartarmizi/OmniCloud](https://github.com/dimartarmizi/OmniCloud) `MIT` - OmniCloud is a full-stack cloud drive aggregation platform that presents multiple storage providers through a single, consistent workspace.

[0xErwin1/dbflux](https://github.com/0xErwin1/dbflux) `MIT / Apache-2.0` - A fast, keyboard-first database client built with Rust and GPUI.

[Noooste/garage-ui](https://github.com/Noooste/garage-ui) `MIT` - Garage Admin UI with OIDC and team access control.

## Proxies & gateways

[drakkan/sftpgo](https://github.com/drakkan/sftpgo) `AGPL-3.0` - Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob.

[gaul/s3proxy](https://github.com/gaul/s3proxy) `Apache-2.0` - Access other storage backends via the S3 API.

[oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) `Apache-2.0` - S3 Reverse Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).

[anomalizer/ngx_aws_auth](https://github.com/anomalizer/ngx_aws_auth) `BSD-2-Clause` - nginx module to proxy to authenticated AWS services.

[ebogdum/callfs](https://github.com/ebogdum/callfs) `MIT` - CallFS is an ultra-lightweight, high-performance REST API filesystem that provides precise Linux filesystem semantics over various backends including local filesystem, Amazon S3, and distributed peer networks.

[pottava/aws-s3-proxy](https://github.com/pottava/aws-s3-proxy) `MIT` - Reverse proxy for AWS S3 with basic authentication.

## Backup, recovery & synchronization

[databasus/databasus](https://github.com/databasus/databasus) `Apache-2.0` - PostgreSQL backup tool with Point-In-Time-Recovery and restore verification.

[eduardolat/pgbackweb](https://github.com/eduardolat/pgbackweb) `AGPL-3.0` - Effortless PostgreSQL backups with a user-friendly web interface.

[maxisam/mgob](https://github.com/maxisam/mgob) `MIT` - MongoDB dockerized backup agent. Runs schedule backups with retention, S3 & SFTP upload, notifications, instrumentation with Prometheus and more.

[hesprs/sync-engine](https://github.com/hesprs/sync-engine) `MIT` - The next-generation Obsidian syncing plugin. Fast. Free. Extend with Modules.

## Development & integrations

[knadh/koanf](https://github.com/knadh/koanf) `MIT` - Simple, extremely lightweight, extensible, configuration management library for Go. Supports JSON, TOML, YAML, env, command line, file, S3 etc. Alternative to viper.

[piskvorky/smart_open](https://github.com/piskvorky/smart_open) `MIT` - Utils for streaming large files (S3, HDFS, gzip, bz2).

[haydenbleasel/files-sdk](https://github.com/haydenbleasel/files-sdk) `MIT` - A unified storage SDK for object and blob backends. One small, honest API. Web-standards I/O.

[good-lly/s3mini](https://github.com/good-lly/s3mini) `MIT` - Tiny S3 client. Edge computing ready. No-dep. In Typescript.

[bradleyg/django-s3direct](https://github.com/bradleyg/django-s3direct) `MIT` - Directly upload files to S3 compatible services with Django.

[robinrodricks/FluentStorage](https://github.com/robinrodricks/FluentStorage) `MIT` - .NET polycloud storage framework which provides a unified polycloud API across 15+ clouds for Object manipulation, File uploads/downloads, File streaming/seeking, Directory upload/download, Object metadata, Versioning, Tags, Storage tier/class, Presigned URLs and more.

## Security & testing

[sa7mon/S3Scanner](https://github.com/sa7mon/S3Scanner) `MIT` - Scan for misconfigured S3 buckets across S3-compatible APIs.

[jordanpotti/AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) `MIT` - Security Tool to Look For Interesting Files in S3 Buckets.

[0xsha/CloudBrute](https://github.com/0xsha/CloudBrute) `MIT` - Awesome cloud enumerator.

[SharonBrizinov/s3viewer](https://github.com/SharonBrizinov/s3viewer) `MIT` - Storage Explorer - Publicly open storage viewer (Amazon S3 Bucket, Azure Blob, FTP server, HTTP Index Of/).

[gwen001/s3-buckets-finder](https://github.com/gwen001/s3-buckets-finder) `MIT` - Find AWS S3 buckets and test their permissions.

## Automation & deployment

[cloudkj/scar](https://github.com/cloudkj/scar) `MIT` - Deploy static websites in seconds - with HTTPS, a global CDN, and custom domains.

[tmspzz/Rome](https://github.com/tmspzz/Rome) `MIT` - Carthage cache for S3, Minio, Ceph, Google Storage, Artifactory and many others.

[pgherveou/gulp-awspublish](https://github.com/pgherveou/gulp-awspublish) `MIT` - gulp plugin to publish files to amazon s3.

[aminueza/terraform-provider-minio](https://github.com/aminueza/terraform-provider-minio) `AGPL-3.0` - Terraform provider for MinIO and S3-compatible storage (R2, B2, Hetzner, Spaces) — buckets, IAM, replication, lifecycle, encryption & more.

[multiplegeorges/vue-cli-plugin-s3-deploy](https://github.com/multiplegeorges/vue-cli-plugin-s3-deploy) `MIT` - A vue-cli plugin that uploads your built Vue.js project to an S3 bucket.
