# Awesome S3

A curated list of projects, tools, and resources related to S3-compatible object storage.

Projects released under OSI-approved open-source licenses are preferred, but projects with proprietary or commercial licenses are also welcome.

Contributions to this list are welcome. See [CONTRIBUTING.md](./CONTRIBUTING.md).


## Table of contents

- [Storage clients & tools](#storage-clients--tools) `35`
- [Proxies & gateways](#proxies--gateways) `11`
- [Backup, recovery & synchronization](#backup-recovery--synchronization) `19`
- [Development & integrations](#development--integrations) `47`
- [Security & testing](#security--testing) `17`
- [Automation & deployment](#automation--deployment) `12`
- [S3-compatible storage servers](#s3-compatible-storage-servers) `5`
- [Data processing & monitoring](#data-processing--monitoring) `5`
- [Documentation & references](#documentation--references) `1`


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

[mishudark/s3-parallel-put](https://github.com/mishudark/s3-parallel-put) `MIT` - Parallel uploads to Amazon AWS S3.

[zsuroy/ctty](https://github.com/zsuroy/ctty) `MIT` - A lightweight, all-in-one connection manager — SSH, Serial, SFTP, Telnet, FTP, WebDAV and S3 in a single TUI.

[rgcsekaraa/brows3](https://github.com/rgcsekaraa/brows3) `MIT` - Super fast open-source S3 browser, S3 explorer, and desktop client for Amazon S3, MinIO, Cloudflare R2, Wasabi, and other S3-compatible storage.

[mkloubert/vscode-remote-workspace](https://github.com/mkloubert/vscode-remote-workspace) `LGPL-3.0` - Multi protocol support for handling remote files like local ones in Visual Studio Code.

[go-to-k/cls3](https://github.com/go-to-k/cls3) `MIT` - The CLI tool "cls3" is to CLear S3 Buckets. It empties (so deletes all objects and versions/delete-markers in) S3 Buckets or deletes the buckets themselves.

[koblas/s3-cli](https://github.com/koblas/s3-cli) `MIT` - Go version of s3cmd.

[rzrbld/adminio-ui](https://github.com/rzrbld/adminio-ui) `MIT` - a simple admin ui for min.io (minio) s3 server.

[dev2ex/twig](https://github.com/dev2ex/twig) `GPL-3.0` - Dual-pane Android file manager: local storage, archives, FTP, SFTP, SMB, WebDAV, S3, restic and Jellyfin/Emby in one tree. Plain Kotlin, compact APK.

[tsub/s3-edit](https://github.com/tsub/s3-edit) `MIT` - Edit files directly on Amazon S3 from the command line using your preferred text editor.

[lmammino/s3st](https://github.com/lmammino/s3st) `MIT` - A command line utility that allows you to stream data from multiple S3 objects directly into your terminal.

[akrylysov/bsimp](https://github.com/akrylysov/bsimp) `Apache-2.0` - Minimalistic S3-backed audio library.

[talo58948/herdfs](https://github.com/talo58948/herdfs) `MIT` - Open, pluggable shared filesystem: FUSE clients, one authority, any S3 bucket.

[eyebrowkang/garage-admin-console](https://github.com/eyebrowkang/garage-admin-console) `AGPL-3.0` - A modern web-based administration interface for managing Garage distributed object storage clusters.

[yixian-huang/imgli](https://github.com/yixian-huang/imgli) `AGPL-3.0` - Self-hosted image hosting — one leap to a link. Single binary, S3-compatible storage, content moderation, and PicGo integration.

[flightlesstux/S3-Directory-Listing](https://github.com/flightlesstux/S3-Directory-Listing) `MIT` - A lightweight, zero-dependency UI that turns any AWS S3 bucket into a clean, navigable file browser. Drop 4 files, done.

[dtan4/s3url](https://github.com/dtan4/s3url) `MIT` - Generate S3 object pre-signed URL in one command.

[romanzdk/s3-web-browser](https://github.com/romanzdk/s3-web-browser) `MIT` - A Flask-based S3 Browser for navigating AWS S3 buckets and files with secure, temporary URL generation for object sharing.

[xtream1101/s3-concat](https://github.com/xtream1101/s3-concat) `MIT` - Concat multiple files in s3.

[miroshnikov/filefive](https://github.com/miroshnikov/filefive) `GPL-3.0` - FileFive is a GUI dual-panel file transfer, synchronization and backup manager for Windows, macOS and Linux with support for SFTP, FTP and Amazon S3.

[shvc/s3cli](https://github.com/shvc/s3cli) `MIT` - Command line tool for S3.

[pteich/us3ui](https://github.com/pteich/us3ui) `MIT` - Universal Cross-Platform native FileManager for s3, Object Storage, SFTP, FTP.

[chrishein/s3_uploader](https://github.com/chrishein/s3_uploader) `MIT` - Multithreaded recursive directory upload to S3 using FOG.

[AnderEnder/s3find-rs](https://github.com/AnderEnder/s3find-rs) `BSD-2-Clause` - A command line utility to walk an Amazon S3 hierarchy. s3find is an analog of find for Amazon S3.

[zwpaper/dilu](https://github.com/zwpaper/dilu) `Apache-2.0` - A colorful CLI client with icons for accessing data via OpenDAL.

[ashwathstephen/sairo](https://github.com/ashwathstephen/sairo) `Apache-2.0` - Self-hosted S3 storage browser with cost intelligence, optimization recommendations, and AI-powered analytics. Works with AWS, MinIO, R2, Wasabi, and any S3-compatible endpoint.

[guicamest/GDuplicate-Finder](https://github.com/guicamest/GDuplicate-Finder) - GDuplicate Finder - A Groovy way to find duplicates among your computer and network shares!

[↑ Back to top](#table-of-contents)


## Proxies & gateways

[drakkan/sftpgo](https://github.com/drakkan/sftpgo) `AGPL-3.0` - Full-featured and highly configurable SFTP, HTTP/S, FTP/S and WebDAV server - S3, Google Cloud Storage, Azure Blob.

[gaul/s3proxy](https://github.com/gaul/s3proxy) `Apache-2.0` - Access other storage backends via the S3 API.

[oxyno-zeta/s3-proxy](https://github.com/oxyno-zeta/s3-proxy) `Apache-2.0` - S3 Reverse Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).

[anomalizer/ngx_aws_auth](https://github.com/anomalizer/ngx_aws_auth) `BSD-2-Clause` - nginx module to proxy to authenticated AWS services.

[ebogdum/callfs](https://github.com/ebogdum/callfs) `MIT` - CallFS is an ultra-lightweight, high-performance REST API filesystem that provides precise Linux filesystem semantics over various backends including local filesystem, Amazon S3, and distributed peer networks.

[pottava/aws-s3-proxy](https://github.com/pottava/aws-s3-proxy) `MIT` - Reverse proxy for AWS S3 with basic authentication.

[qinguoyi/osproxy](https://github.com/qinguoyi/osproxy) `Apache-2.0` - Distributed object storage proxy with one-click Docker deployment.

[harshavardhana/s3www](https://github.com/harshavardhana/s3www) `Apache-2.0` - Serve static files from any S3 compatible object storage services (Let's Encrypt ready).

[axl89/s3cr3t](https://github.com/axl89/s3cr3t) `GPL-3.0` - A supercharged S3 reverse proxy.

[qinguoyi/osproxy-grpc](https://github.com/qinguoyi/osproxy-grpc) `Apache-2.0` - gRPC implementation of osproxy, supporting RPC and API on the same port via grpc-gateway, with one-click Docker deployment.

[DullJZ/s3-balance](https://github.com/DullJZ/s3-balance) - Automatic load balancing for S3-compatible object storage, exposing a unified S3 API.

[↑ Back to top](#table-of-contents)


## Backup, recovery & synchronization

[databasus/databasus](https://github.com/databasus/databasus) `Apache-2.0` - PostgreSQL backup tool with Point-In-Time-Recovery and restore verification.

[eduardolat/pgbackweb](https://github.com/eduardolat/pgbackweb) `AGPL-3.0` - Effortless PostgreSQL backups with a user-friendly web interface.

[maxisam/mgob](https://github.com/maxisam/mgob) `MIT` - MongoDB dockerized backup agent. Runs schedule backups with retention, S3 & SFTP upload, notifications, instrumentation with Prometheus and more.

[hesprs/sync-engine](https://github.com/hesprs/sync-engine) `MIT` - The next-generation Obsidian syncing plugin. Fast. Free. Extend with Modules.

[mrichtarsky/glacier_deep_archive_backup](https://github.com/mrichtarsky/glacier_deep_archive_backup) `GPL-3.0` - Extremely low cost, off-site backup/restore using AWS S3 Glacier Deep Archive.

[maxisam/mgob](https://github.com/maxisam/mgob) `MIT` - MongoDB dockerized backup agent. Runs schedule backups with retention, S3 & SFTP upload, notifications, instrumentation with Prometheus and more.

[marckohlbrugge/rclown](https://github.com/marckohlbrugge/rclown) `O'Saasy` - Friendly web UI for backing up your object storage buckets.

[istepanov/docker-backup-to-s3](https://github.com/istepanov/docker-backup-to-s3) `MIT` - Docker container that periodically backups files to Amazon S3 using s3cmd and cron.

[badwatt/wrestic](https://github.com/badwatt/wrestic) `LGPL-3.0` - A wrapper around restic built in rust.

[Starofall/S3HyperSync](https://github.com/Starofall/S3HyperSync) `MIT` - S3HyperSync is a high-performance, memory-efficient, and cost-effective tool for synchronizing files between S3-compatible storage services.

[jeanbmar/s3-sync-client](https://github.com/jeanbmar/s3-sync-client) `MIT` - AWS CLI s3 sync command for Node.js.

[nidor1998/s3sync](https://github.com/nidor1998/s3sync) `Apache-2.0` - A reliable, flexible, and fast synchronization tool for S3.

[peter-evans/s3-backup](https://github.com/peter-evans/s3-backup) `MIT` - A GitHub action to mirror a repository to S3 compatible object storage.

[ulver2812/aws-s3-backup](https://github.com/ulver2812/aws-s3-backup) `MIT` - This app allows you to use AWS (Amazon Web Services) S3 as backup system for desktop environments.

[llangit/lambda-mongocluster-s3](https://github.com/llangit/lambda-mongocluster-s3) `MIT` - Backup MongoDB cluster database to AWS S3 via a Lambda function.

[DahanItamar/DockNest](https://github.com/DahanItamar/DockNest) `AGPL-3.0` - Self-hosted Docker backup and restore with a visual server map. Move sites between servers safely, encrypted SFTP or S3 storage, verified restores.

[gluonfield/dgbr](https://github.com/gluonfield/dgbr) `Apache-2.0` - Dgraph backup restore tool to/from AWS S3 bucket.

[dawiddyd/resticopia](https://github.com/dawiddyd/resticopia) `GPL-2.0-only` - A mobile Android application that enables efficient and straightforward data backups powered by Restic backup software.

[hu3rror/memos-litestream](https://github.com/hu3rror/memos-litestream) `GPL-3.0` - Run memos with litestream.

[shellharbor/backfort](https://github.com/shellharbor/backfort) `MIT` - Backfort is a secure Linux backup and disaster recovery tool for files and Docker Compose. Create encrypted, compressed, verifiable backups with age, GPG, Minisign, rclone, S3-compatible storage, retention policies, database dumps, atomic publishing, safe restore, watchdog checks, and instant recovery workflows for servers.

[↑ Back to top](#table-of-contents)


## Development & integrations

[knadh/koanf](https://github.com/knadh/koanf) `MIT` - Simple, extremely lightweight, extensible, configuration management library for Go. Supports JSON, TOML, YAML, env, command line, file, S3 etc. Alternative to viper.

[piskvorky/smart_open](https://github.com/piskvorky/smart_open) `MIT` - Utils for streaming large files (S3, HDFS, gzip, bz2).

[haydenbleasel/files-sdk](https://github.com/haydenbleasel/files-sdk) `MIT` - A unified storage SDK for object and blob backends. One small, honest API. Web-standards I/O.

[good-lly/s3mini](https://github.com/good-lly/s3mini) `MIT` - Tiny S3 client. Edge computing ready. No-dep. In Typescript.

[bradleyg/django-s3direct](https://github.com/bradleyg/django-s3direct) `MIT` - Directly upload files to S3 compatible services with Django.

[robinrodricks/FluentStorage](https://github.com/robinrodricks/FluentStorage) `MIT` - .NET polycloud storage framework which provides a unified polycloud API across 15+ clouds for Object manipulation, File uploads/downloads, File streaming/seeking, Directory upload/download, Object metadata, Versioning, Tags, Storage tier/class, Presigned URLs and more.

[hairyhenderson/go-fsimpl](https://github.com/hairyhenderson/go-fsimpl) `MIT` - Go io/fs.FS filesystem implementations for various URL schemes.

[danielfrg/s3contents](https://github.com/danielfrg/s3contents) `Apache-2.0` - Jupyter Notebooks in S3 - Jupyter Contents Manager implementation.

[wayjam/picgo-plugin-s3](https://github.com/wayjam/picgo-plugin-s3) `MIT` - PicGo S3 plugin.

[good-lly/lowstorage](https://github.com/good-lly/lowstorage) `MIT` - Simple, fast, object pseudo-database for S3-compatible storages using JSON or Msgpack.

[liormizr/s3path](https://github.com/liormizr/s3path) `Apache-2.0` - s3path is a pathlib extension for AWS S3 Service.

[jpetrucciani/bucketstore](https://github.com/jpetrucciani/bucketstore) `MIT` - A simple library for interacting with Amazon S3.

[abhay-ramesh/pushduck](https://github.com/abhay-ramesh/pushduck) `MIT` - Add file uploads to any web application. Secure, edge-ready.

[jszwec/s3fs](https://github.com/jszwec/s3fs) `MIT` - S3 FileSystem (fs.FS) implementation.

[jeffminsungkim/nestjs-multer-extended](https://github.com/jeffminsungkim/nestjs-multer-extended) `MIT` - Extended MulterModule for NestJS with flexible S3 upload and helpful features.

[aloneguid/stowage](https://github.com/aloneguid/stowage) `Apache-2.0` - Bloat-free, no BS cloud storage SDK.

[justindujardin/pathy](https://github.com/justindujardin/pathy) `Apache-2.0` - pathlib.Path style classes for local and cloud bucket storage.

[bradenmacdonald/s3-lite-client](https://github.com/bradenmacdonald/s3-lite-client) `MIT` - A lightweight but powerful JavaScript S3 client.

[theriverman/django-minio-backend](https://github.com/theriverman/django-minio-backend) `MIT` - Minio Backend for Django.

[DiTo97/deepagents-backends](https://github.com/DiTo97/deepagents-backends) `MIT` - S3, PostgreSQL, Azure Blob, GCS, MongoDB, and Redis remote backends for LangChain Deep Agents.

[leoafarias/neardb](https://github.com/leoafarias/neardb) `MIT` - Simple document db made for infinitely scalable globally distributed reads.

[lostatc/acid-store](https://github.com/lostatc/acid-store) `Apache-2.0` - A Rust library for secure, deduplicated, and transactional data storage.

[taylorfinnell/awscr-s3](https://github.com/taylorfinnell/awscr-s3) `MIT` - A Crystal shard for S3 and compatible services.

[frostealth/yii2-aws-s3](https://github.com/frostealth/yii2-aws-s3) `MIT` - An Amazon S3 component for Yii2.

[svtslv/nestjs-s3](https://github.com/svtslv/nestjs-s3) `MIT` - S3 module for Nest.

[jeanbmar/payload-s3-upload](https://github.com/jeanbmar/payload-s3-upload) `MIT` - Send Payload CMS uploads to Amazon S3.

[bluedenim/log4j-s3-search](https://github.com/bluedenim/log4j-s3-search) `MIT` - Log4j appender with S3, Azure, Google Cloud, and search publishing.

[roeap/object-store-python](https://github.com/roeap/object-store-python) `Apache-2.0` - Python bindings and arrow integration for the rust object_store crate.

[developmentforpeople/dfp_external_storage](https://github.com/developmentforpeople/dfp_external_storage) `MIT` - Simplest cloud file management for Frappe / ERPNext. S3 compatible external bucket can be assigned per Frappe folder, allowing you to fine-tune the location of your Frappe / ERPNext "File"s: within local filesystem or to exteral S3 bucket.

[loune/s3leveldown](https://github.com/loune/s3leveldown) `MIT` - An implementation of LevelDOWN that uses Amazon S3. Turn your S3 bucket into a DB.

[TemryL/ComfyS3](https://github.com/TemryL/ComfyS3) `GPL-3.0` - ComfyS3 seamlessly integrates with Amazon S3 in ComfyUI. This open-source project provides custom nodes for effortless loading and saving of images, videos, and checkpoint models directly from S3 buckets within the ComfyUI graph interface.

[eleven26/goss](https://github.com/eleven26/goss) `MIT` - A lightweight Go library for cloud storage, compatible with the Amazon S3 protocol and supporting Alibaba Cloud OSS, Tencent Cloud COS, Qiniu Cloud, Huawei Cloud, AWS S3, and MinIO.

[DyfanJones/s3fs](https://github.com/DyfanJones/s3fs) `MIT` - Access Amazon Web Service 'S3' as if it were a file system. File system 'API' design around R package 'fs'.

[turgutahmet/kolay-xlsx-stream](https://github.com/turgutahmet/kolay-xlsx-stream) `MIT` - Stream millions of rows to XLSX with O(1) memory and direct S3 multipart upload. Laravel-friendly. PHPSpreadsheet alternative for large exports.

[nikeee/lean-s3](https://github.com/nikeee/lean-s3) - A small and fast S3 client without the clutter.

[mlhpdx/seekable-s3-stream](https://github.com/mlhpdx/seekable-s3-stream) `MIT` - Code library that uses S3's API to provide an efficient random-access (seekable) Stream implementation for use in code where efficient network I/O is paramount.

[IamTugy/pyminio](https://github.com/IamTugy/pyminio) `MIT` - Pyminio is a python client wrapped like the os module to control minio server.

[newapplesho/aws-sdk-smalltalk](https://github.com/newapplesho/aws-sdk-smalltalk) `MIT` - AWS SDK for Smalltalk.

[ttax00/obsidian-s3](https://github.com/ttax00/obsidian-s3) `MIT` - An Obsidian plugin for storage and retrieval of media attachments on S3 compatible services.

[algoflows/zig-s3](https://github.com/algoflows/zig-s3) `MIT` - A simple and efficient Zig native S3 client library, supporting AWS S3 and S3-compatible services like MINIO.

[Ajayvarmaramineni/BYOC](https://github.com/Ajayvarmaramineni/BYOC) `Apache-2.0` - One storage API for Google Drive, Nextcloud, and S3-compatible clouds, in TypeScript and Python.

[jessestuart/gatsby-source-s3-image](https://github.com/jessestuart/gatsby-source-s3-image) - GatsbyJS plugin to source images from S3-compliant APIs, with EXIF-extracting superpowers.

[mlhpdx/s3-upload-stream](https://github.com/mlhpdx/s3-upload-stream) `MIT` - Code library that provides a Stream implementation that makes working with uploads to S3 easier where the size of the content isn't known a priori. It holds only partial content in memory (works with large objects), and is compatible with code libraries that work with output streams.

[chris23lngr/vS3](https://github.com/chris23lngr/vS3) `MIT` - S3 storage toolkit built for the web.

[Arrmlet/tracecraft](https://github.com/Arrmlet/tracecraft) `MIT` - The black box for AI agents — record every session, referee every task claim. Live mirroring + atomic coordination in a bucket YOU own. No server.

[Alex1990/tiny-oss](https://github.com/Alex1990/tiny-oss) `MIT` - A tiny object storage SDK focused on uploading.

[↑ Back to top](#table-of-contents)


## Security & testing

[sa7mon/S3Scanner](https://github.com/sa7mon/S3Scanner) `MIT` - Scan for misconfigured S3 buckets across S3-compatible APIs.

[jordanpotti/AWSBucketDump](https://github.com/jordanpotti/AWSBucketDump) `MIT` - Security Tool to Look For Interesting Files in S3 Buckets.

[0xsha/CloudBrute](https://github.com/0xsha/CloudBrute) `MIT` - Awesome cloud enumerator.

[SharonBrizinov/s3viewer](https://github.com/SharonBrizinov/s3viewer) `MIT` - Storage Explorer - Publicly open storage viewer (Amazon S3 Bucket, Azure Blob, FTP server, HTTP Index Of/).

[gwen001/s3-buckets-finder](https://github.com/gwen001/s3-buckets-finder) `MIT` - Find AWS S3 buckets and test their permissions.

[koenrh/s3enum](https://github.com/koenrh/s3enum) `ISC` - Fast and stealthy Amazon S3 bucket enumeration tool for pentesters.

[simonw/s3-credentials](https://github.com/simonw/s3-credentials) `Apache-2.0` - A tool for creating credentials for accessing S3 buckets.

[gaul/are-we-consistent-yet](https://github.com/gaul/are-we-consistent-yet) `Apache-2.0` - Compare eventual consistency of object stores.

[clarketm/s3recon](https://github.com/clarketm/s3recon) `MIT` - Amazon S3 bucket finder and crawler.

[AlecBlance/S3BucketList](https://github.com/AlecBlance/S3BucketList) `MIT` - Chrome and Firefox extension that lists Amazon S3 Buckets while browsing.

[random-robbie/AWS-Scanner](https://github.com/random-robbie/AWS-Scanner) `Unlicense` - Scans a list of websites for Cloudfront or S3 Buckets.

[michenriksen/bucketlist](https://github.com/michenriksen/bucketlist) `MIT` - Amazon S3 bucket enumerator and crawler.

[Robothy/local-s3](https://github.com/Robothy/local-s3) `Apache-2.0` - An Amazon S3 mock service for testing and local development.

[nikhil1232/Bucket-Flaws](https://github.com/nikhil1232/Bucket-Flaws) - Bucket Flaws ( S3 Bucket Mass Scanner ): A Simple Lightweight Script to Check for Common S3 Bucket Misconfigurations.

[random-robbie/mass-s3-bucket-tester](https://github.com/random-robbie/mass-s3-bucket-tester) `Unlicense` - This tests a list of s3 buckets to see if they have dir listings enabled or if they are uploadable.

[Kiinitix/Colossus](https://github.com/Kiinitix/Colossus) `Apache-2.0` - Secure File Storage in Cloud Computing using Hybrid Cryptography Algorithms. Colossus ensures security of the user’s data stored on cloud (AWS S3) by providing a tool that helps to encrypt files using AES and RSA. The user receives the key via email.

[abhinavbom/clara](https://github.com/abhinavbom/clara) - Serverless, real-time, ClamAV+Yara scanning for your S3 Buckets.

[↑ Back to top](#table-of-contents)


## Automation & deployment

[cloudkj/scar](https://github.com/cloudkj/scar) `MIT` - Deploy static websites in seconds - with HTTPS, a global CDN, and custom domains.

[tmspzz/Rome](https://github.com/tmspzz/Rome) `MIT` - Carthage cache for S3, Minio, Ceph, Google Storage, Artifactory and many others.

[pgherveou/gulp-awspublish](https://github.com/pgherveou/gulp-awspublish) `MIT` - gulp plugin to publish files to amazon s3.

[aminueza/terraform-provider-minio](https://github.com/aminueza/terraform-provider-minio) `AGPL-3.0` - Terraform provider for MinIO and S3-compatible storage (R2, B2, Hetzner, Spaces) — buckets, IAM, replication, lifecycle, encryption & more.

[multiplegeorges/vue-cli-plugin-s3-deploy](https://github.com/multiplegeorges/vue-cli-plugin-s3-deploy) `MIT` - A vue-cli plugin that uploads your built Vue.js project to an S3 bucket.

[bgahagan/git-remote-s3](https://github.com/bgahagan/git-remote-s3) `MIT` - Push and pull git repos to/from an s3 bucket, encrypted using gpg.

[dmfutcher/git-s3-push](https://github.com/dmfutcher/git-s3-push) `MIT` - Deploy your git repo to an S3 bucket.

[tpunder/fm-sbt-s3-resolver](https://github.com/tpunder/fm-sbt-s3-resolver) `Apache-2.0` - SBT Plugin that adds support for resolving and publishing using Amazon S3.

[liddiard/google-sheet-s3](https://github.com/liddiard/google-sheet-s3) `MIT` - Google Apps Script that publishes a Google Sheet to Amazon S3 as a JSON file. Auto-updates on edit & maintains data types. Creates an array of objects keyed by column header.

[ricsanfre/ansible-role-minio](https://github.com/ricsanfre/ansible-role-minio) `MIT` - Ansible role for installing and configuring MinIO.

[AdamShannag/volare](https://github.com/AdamShannag/volare) `MIT` - Kubernetes volume populator.

[jonelantha/gatsby-s3-action](https://github.com/jonelantha/gatsby-s3-action) `MIT` - Deploy a Gatsby Project to an AWS S3 bucket (optional Cloudfront support).

[richarvey/s3redirect](https://github.com/richarvey/s3redirect) `GPL-3.0` - Turn S3 into a URL redirect website using lambda and NO database.

[↑ Back to top](#table-of-contents)


## S3-compatible storage servers

[uroni/hs5](https://github.com/uroni/hs5) `LGPL-3.0` - High-performance scale-up self-hosted s3-compatible object storage (hs5).

[soulteary/otterio](https://github.com/soulteary/otterio) `Apache-2.0` - A lightweight S3-compatible object storage service derived from the Apache-licensed MinIO codebase.

[AngusKit/AngusStorage](https://github.com/AngusKit/AngusStorage) `GPL-3.0` - Enterprise-grade unified file storage service designed for hybrid cloud environments.

[luiscib3r/Telezon-S3](https://github.com/luiscib3r/Telezon-S3) `MIT` - Telezon S3 is a storage service that implements Amazon S3-compatible API using Telegram as the storage backend. It allows you to store and retrieve files using standard S3 clients while leveraging Telegram's infrastructure for actual file storage.

[artabramov/hidden](https://github.com/artabramov/hidden) `Apache-2.0` - Encrypted self-hosted S3 storage.

[↑ Back to top](#table-of-contents)


## Data processing & monitoring

[ribbybibby/s3_exporter](https://github.com/ribbybibby/s3_exporter) `Apache-2.0` - Exports Prometheus metrics about S3 buckets and objects

[simonw/s3-ocr](https://github.com/simonw/s3-ocr) `Apache-2.0` - Tools for running OCR against files stored in S3.

[mmolimar/kafka-connect-fs](https://github.com/mmolimar/kafka-connect-fs) `Apache-2.0` - Kafka Connect FileSystem Connector.

[gbram1/streamhouse](https://github.com/gbram1/streamhouse) `Apache-2.0` - Open-source event streaming platform built on S3. Kafka-compatible APIs, built-in SQL engine, schema registry — one Rust binary replaces Kafka + ZooKeeper + KSQL. Retention costs pennies, not thousands.

[alash3al/xyr](https://github.com/alash3al/xyr) `Apache-2.0` - Query any data source using SQL, works with the local filesystem, s3, and more. It should be a very tiny and lightweight alternative to AWS Athena, Presto ... etc.

[↑ Back to top](#table-of-contents)


## Documentation & references

[gaul/undocumented-s3-apis](https://github.com/gaul/undocumented-s3-apis) - Undocumented Amazon S3 APIs and third-party extensions.

[↑ Back to top](#table-of-contents)
