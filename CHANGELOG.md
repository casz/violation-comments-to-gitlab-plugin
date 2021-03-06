# Violation Comments to GitLab changelog
Changelog of Violation Comments to GitLab plugin for Jenkins.
## 1.27
### GitHub [#10](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/issues/10) Global config needs to be saved first, or NPE will happen

**Avoid need to save global config before use #10**


[facbbea73c6f76b](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/facbbea73c6f76b8c515c5ac69930952a56111e9) Tomas Bjerre *2018-02-22 19:37:11*


## 1.26
### No issue

**PCLint**


[7249ae415f3853d](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/7249ae415f3853dc982476fb7531e328530d6fa8) Tomas Bjerre *2018-02-13 20:13:26*


## 1.25
### No issue

**PCLint**


[9a5adfb19a4625d](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/9a5adfb19a4625df2ff0d278c414b67a0dcb642d) Tomas Bjerre *2018-02-13 19:21:08*


## 1.24
### No issue

**Refactoring**


[669fc52d95825cc](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/669fc52d95825ccd0f6661b65e4b6c0ac45f931b) Tomas Bjerre *2018-01-28 15:03:42*

**Jenkinsfile**


[22f12c73e6e44ce](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/22f12c73e6e44ceb2c853e23eff7b76b183c6c57) Tomas Bjerre *2018-01-27 18:32:50*


## 1.23
### No issue

**Google error-prone**


[a42ac995850c8c1](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/a42ac995850c8c1ce6be6dea7710599f04eea173) Tomas Bjerre *2018-01-14 12:04:31*


## 1.22
### No issue

**Relocating to correct Java identifier**


[6becb07178f0ec4](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/6becb07178f0ec43eb33f0a84b69b4feb4cffd00) Tomas Bjerre *2017-12-31 11:58:55*


## 1.20
### No issue

**Fixing encoding issues**


[3e2af04b327f268](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/3e2af04b327f26839db8a20a653f8a2a41cf0cdd) Tomas Bjerre *2017-12-25 20:01:30*

**Bumping version to fix faulty release**


[73dd2806c3ec2c1](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/73dd2806c3ec2c146e91893a14bc329dc6f05dd9) Tomas Bjerre *2017-12-22 19:56:13*


## 1.19
### No issue

**DocFX parsing JSON with Gson, not ScriptEngine**


[449b39057ee5687](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/449b39057ee568773d022f8268a3d22ba07ead86) Tomas Bjerre *2017-12-22 12:57:39*


## 1.18
### No issue

**DocFX**


[04057d3c556f9e9](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/04057d3c556f9e9332c62dfcfcd9a2b244d8bc32) Tomas Bjerre *2017-12-21 15:00:37*


## 1.17
### No issue

**Accepting PMD files without ruleset-tag**


[ab716dd2c83d527](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/ab716dd2c83d5270c6576fca8f991a54ac4585df) Tomas Bjerre *2017-12-07 16:13:04*

**Doc**


[15b4097739a44c5](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/15b4097739a44c5985aa1f57f8221863eb67e55d) Tomas Bjerre *2017-11-18 13:50:20*


## 1.16
### GitHub [#8](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/issues/8) Could not get GitLab project

**Better error message if project cannot be found #8**


[88c4817400b182a](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/88c4817400b182aa6e7b2fe1cc714be2f8200414) Tomas Bjerre *2017-11-01 18:49:22*


## 1.15
### No issue

**Resharper WikiUrl**


[1fd3145fcd48d2e](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/1fd3145fcd48d2ea3f3669a4e22cd09b1fa5c136) Tomas Bjerre *2017-10-13 11:35:09*


## 1.14
### No issue

**Added handling for empty IssueType Description attributes for Resharper**


[854f6f787a0a52a](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/854f6f787a0a52aa210d247bce6694d277fc8a55) Tomas Bjerre *2017-10-09 16:58:00*


## 1.13
### No issue

**Allowing reporter to be unset**


[48ade8a79d4e978](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/48ade8a79d4e97870e8e3dccc14fcde6e2b28d4d) Tomas Bjerre *2017-09-26 19:44:30*

**Doc**


[085c5b5751e5b8e](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/085c5b5751e5b8e1724f7d2d577397f8f6831213) Tomas Bjerre *2017-09-03 08:13:59*


## 1.12
### No issue

**Keeping comments and adjusting checkstyle**

 * Checkstyle now allows empty source attribute. 
 * Comments can optionaly be kept and not removed when new comments are added. 
 * Will no longer re-create identical comments. 
 * Using API V4 

[3ec3b9a97663a01](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/3ec3b9a97663a019c7daa15342d98e0d8283cc63) Tomas Bjerre *2017-09-02 14:49:39*

**Keeping comments and adjusting checkstyle**

 * Checkstyle now allows empty source attribute. 
 * Comments can optionaly be kept and not removed when new comments are added. 
 * Will no longer re-create identical comments. 
 * Using GitLab API V4 

[5780a2457e06631](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/5780a2457e066310f164985b8666ccd9fcf68321) Tomas Bjerre *2017-09-02 09:30:44*


## 1.11
### No issue

**Ignoring violation configs with null config**


[5f8c94518aeaf9a](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/5f8c94518aeaf9a3d3207ff4aa3bcbd93baa47d0) Tomas Bjerre *2017-08-11 11:36:58*


## 1.10
### No issue

**Ignoring violation configs with null config**


[b6720937a4c1e04](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/b6720937a4c1e04881acc590751843d3d7a27348) Tomas Bjerre *2017-08-11 11:35:05*

**Cleaning**


[8db36c5d2049ae4](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/8db36c5d2049ae4ee89e950566a7b1d9708e5fbc) Tomas Bjerre *2017-07-20 19:33:33*

**doc**


[cf45a5aa041e3c8](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/cf45a5aa041e3c848aa0660b0671e5cd4a1ed638) Tomas Bjerre *2017-07-15 13:11:30*


## 1.9
### No issue

**Bugfix, were unable to save reporter from GUI**


[ad8703d0989ca57](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/ad8703d0989ca57cebf176db9a494269b3ac8a76) Tomas Bjerre *2017-07-15 13:09:22*


## 1.8
### No issue

**Violations-lib 1.29 with reporter field**

 * This breaks backwards compatibilty a bit. Reporter is renamed to Parser and an optional text-field called reporter is introduced. If something like Detekt is used to produce a checkstyle-report, then reporter can be set to Detekt and the parser set to CHECKSTYLE. 

[820577dd8dc4546](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/820577dd8dc454615cce51a9168b2ba75e87266f) Tomas Bjerre *2017-07-15 07:54:40*

**Updating doc on Infer**


[93bc67d232b2521](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/93bc67d232b25219cb374ddbfb73262b78e911f1) Tomas Bjerre *2017-06-23 12:53:38*

**doc**


[1869d23af48a0f1](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/1869d23af48a0f1941e42d4f26bbbf11ae93f90d) Tomas Bjerre *2017-06-13 18:01:27*

**doc**


[1f06fa98af3d4b4](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/1f06fa98af3d4b46543a87562cd81d623279f4f4) Tomas Bjerre *2017-04-22 04:32:55*


## 1.7
### No issue

**Allow String as projectId**


[318bde3205e8ed6](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/318bde3205e8ed62f4e37844686fd35fd4ccd93e) Tomas Bjerre *2017-04-21 17:00:23*


## 1.6
### No issue

**URL in Klocwork**


[8f123582ea0373f](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/8f123582ea0373f9237d782c4e685a64d8280559) Tomas Bjerre *2017-04-11 18:29:45*

**doc**


[4e252dd22d077f8](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/4e252dd22d077f8ef7fa079fac916d6b65506ed2) Tomas Bjerre *2017-04-10 20:17:24*


## 1.5
### No issue

**SbtScalac**


[895fe8717e5a255](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/895fe8717e5a255b69e2b9812f329a78d0bcf0dc) Tomas Bjerre *2017-04-10 18:42:20*

**doc**


[38c25c7f2d22f4e](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/38c25c7f2d22f4ebcef8a85be4eea3c388e3e2bb) Tomas Bjerre *2017-04-10 17:31:51*


## 1.4
### No issue

**Klocwork parser**


[03d28f8442fd2cd](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/03d28f8442fd2cd49cafaaf4898596a4daac9d18) Tomas Bjerre *2017-03-30 17:39:30*

**doc**


[2d9ed88aac0ab80](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/2d9ed88aac0ab8056720ef075fc1bf3ac8372c9a) Tomas Bjerre *2017-03-18 19:25:05*


## 1.3
### No issue

**Persisting severity filter on global config**


[222665cc5b92adb](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/222665cc5b92adb16208d89f61d4f5e9a68e9129) Tomas Bjerre *2017-03-17 20:57:23*


## 1.2
### No issue

**Allow filtering on severity**

 * And reducing logging in server log. 

[f2438c25e94162b](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/f2438c25e94162bb10875d67bd53737a5a4a544c) Tomas Bjerre *2017-03-17 19:44:18*

**doc**


[7e25d0de1f34d17](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/7e25d0de1f34d170b739908ce33cd5fdbfd93fdd) Tomas Bjerre *2017-03-14 18:31:23*

**Jenkinsfile**


[b8e058e54415664](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/b8e058e544156641809e94022fabcb2e0fd66070) Tomas Bjerre *2017-03-10 17:38:13*


## 1.1
### No issue

**doc**


[5767ae9c726bf18](https://github.com/jenkinsci/violation-comments-to-gitlab-plugin/commit/5767ae9c726bf18ad2390130ad21213462b14241) Tomas Bjerre *2017-03-04 09:25:07*


