# $Id$

# Sympa - SYsteme de Multi-Postage Automatique
#
# Copyright (c) 1997, 1998, 1999 Institut Pasteur & Christophe Wolfhugel
# Copyright (c) 1997, 1998, 1999, 2000, 2001, 2002, 2003, 2004, 2005,
# 2006, 2007, 2008, 2009, 2010, 2011 Comite Reseau des Universites
# Copyright (c) 2011, 2012, 2013, 2014, 2015, 2016, 2017 GIP RENATER
# Copyright 2017, 2018, 2019 The Sympa Community. See the AUTHORS.md file at
# the top-level directory of this distribution and at
# <https://github.com/sympa-community/sympa.git>.
#
# This program is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# This program is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with this program.  If not, see <http://www.gnu.org/licenses/>.

nobase_nodist_modules_DATA = \
	Sympa/Constants.pm
nobase_dist_modules_DATA = \
	Sympa/Internals.pod \
	Sympa/Internals/Workflow.pod
nobase_modules_DATA = \
	Sympa.pm \
	Sympa/Alarm.pm \
	Sympa/Aliases.pm \
	Sympa/Aliases/CheckSMTP.pm \
	Sympa/Aliases/External.pm \
	Sympa/Aliases/Template.pm \
	Sympa/Archive.pm \
	Sympa/Bulk.pm \
	Sympa/CommandDef.pm \
	Conf.pm \
	Sympa/ConfDef.pm \
	Sympa/Config.pm \
	Sympa/Config_XML.pm \
	Sympa/Crash.pm \
	Sympa/Database.pm \
	Sympa/DatabaseDescription.pm \
	Sympa/DatabaseDriver.pm \
	Sympa/DatabaseDriver/CSV.pm \
	Sympa/DatabaseDriver/LDAP.pm \
	Sympa/DatabaseDriver/MySQL.pm \
	Sympa/DatabaseDriver/ODBC.pm \
	Sympa/DatabaseDriver/Oracle.pm \
	Sympa/DatabaseDriver/Oracle/St.pm \
	Sympa/DatabaseDriver/PostgreSQL.pm \
	Sympa/DatabaseDriver/SQLite.pm \
	Sympa/DatabaseManager.pm \
	Sympa/DataSource.pm \
	Sympa/DataSource/File.pm \
	Sympa/DataSource/LDAP.pm \
	Sympa/DataSource/LDAP2.pm \
	Sympa/DataSource/List.pm \
	Sympa/DataSource/RemoteDump.pm \
	Sympa/DataSource/RemoteFile.pm \
	Sympa/DataSource/SQL.pm \
	Sympa/Family.pm \
	Sympa/HTML/FormatText.pm \
	Sympa/HTMLDecorator.pm \
	Sympa/HTMLSanitizer.pm \
	Sympa/Language.pm \
	Sympa/List.pm \
	Sympa/List/Config.pm \
	Sympa/List/Users.pm \
	Sympa/ListDef.pm \
	Sympa/ListOpt.pm \
	Sympa/LockedFile.pm \
	Sympa/Log.pm \
	Sympa/Mailer.pm \
	Sympa/Message.pm \
	Sympa/Message/Plugin.pm \
	Sympa/Message/Plugin/FixEncoding.pm \
	Sympa/Message/Template.pm \
	Sympa/Process.pm \
	Sympa/Regexps.pm \
	Sympa/Request.pm \
	Sympa/Request/Collection.pm \
	Sympa/Request/Handler.pm \
	Sympa/Request/Handler/add.pm \
	Sympa/Request/Handler/auth.pm \
	Sympa/Request/Handler/close_list.pm \
	Sympa/Request/Handler/confirm.pm \
	Sympa/Request/Handler/create_automatic_list.pm \
	Sympa/Request/Handler/create_list.pm \
	Sympa/Request/Handler/decl.pm \
	Sympa/Request/Handler/del.pm \
	Sympa/Request/Handler/distribute.pm \
	Sympa/Request/Handler/finished.pm \
	Sympa/Request/Handler/get.pm \
	Sympa/Request/Handler/global_remind.pm \
	Sympa/Request/Handler/global_set.pm \
	Sympa/Request/Handler/global_signoff.pm \
	Sympa/Request/Handler/help.pm \
	Sympa/Request/Handler/import.pm \
	Sympa/Request/Handler/include.pm \
	Sympa/Request/Handler/index.pm \
	Sympa/Request/Handler/info.pm \
	Sympa/Request/Handler/invite.pm \
	Sympa/Request/Handler/last.pm \
	Sympa/Request/Handler/lists.pm \
	Sympa/Request/Handler/modindex.pm \
	Sympa/Request/Handler/move_list.pm \
	Sympa/Request/Handler/move_user.pm \
	Sympa/Request/Handler/open_list.pm \
	Sympa/Request/Handler/reject.pm \
	Sympa/Request/Handler/remind.pm \
	Sympa/Request/Handler/review.pm \
	Sympa/Request/Handler/set.pm \
	Sympa/Request/Handler/signoff.pm \
	Sympa/Request/Handler/stats.pm \
	Sympa/Request/Handler/subscribe.pm \
	Sympa/Request/Handler/unknown.pm \
	Sympa/Request/Handler/update_automatic_list.pm \
	Sympa/Request/Handler/verify.pm \
	Sympa/Request/Handler/which.pm \
	Sympa/Request/Message.pm \
	Sympa/Robot.pm \
	Sympa/Scenario.pm \
	Sympa/Spindle.pm \
	Sympa/Spindle/AuthorizeMessage.pm \
	Sympa/Spindle/AuthorizeRequest.pm \
	Sympa/Spindle/DispatchRequest.pm \
	Sympa/Spindle/DistributeMessage.pm \
	Sympa/Spindle/DoCommand.pm \
	Sympa/Spindle/DoForward.pm \
	Sympa/Spindle/DoMessage.pm \
	Sympa/Spindle/ProcessArchive.pm \
	Sympa/Spindle/ProcessAuth.pm \
	Sympa/Spindle/ProcessAutomatic.pm \
	Sympa/Spindle/ProcessBounce.pm \
	Sympa/Spindle/ProcessDigest.pm \
	Sympa/Spindle/ProcessHeld.pm \
	Sympa/Spindle/ProcessIncoming.pm \
	Sympa/Spindle/ProcessMessage.pm \
	Sympa/Spindle/ProcessModeration.pm \
	Sympa/Spindle/ProcessOutgoing.pm \
	Sympa/Spindle/ProcessRequest.pm \
	Sympa/Spindle/ProcessTask.pm \
	Sympa/Spindle/ProcessTemplate.pm \
	Sympa/Spindle/ResendArchive.pm \
	Sympa/Spindle/ToAlarm.pm \
	Sympa/Spindle/ToArchive.pm \
	Sympa/Spindle/ToAuth.pm \
	Sympa/Spindle/ToAuthOwner.pm \
	Sympa/Spindle/ToDigest.pm \
	Sympa/Spindle/ToEditor.pm \
	Sympa/Spindle/ToHeld.pm \
	Sympa/Spindle/ToList.pm \
	Sympa/Spindle/ToMailer.pm \
	Sympa/Spindle/ToModeration.pm \
	Sympa/Spindle/ToOutgoing.pm \
	Sympa/Spindle/TransformDigestFinal.pm \
	Sympa/Spindle/TransformIncoming.pm \
	Sympa/Spindle/TransformOutgoing.pm \
	Sympa/Spool.pm \
	Sympa/Spool/Archive.pm \
	Sympa/Spool/Auth.pm \
	Sympa/Spool/Automatic.pm \
	Sympa/Spool/Bounce.pm \
	Sympa/Spool/Digest.pm \
	Sympa/Spool/Digest/Collection.pm \
	Sympa/Spool/Held.pm \
	Sympa/Spool/Incoming.pm \
	Sympa/Spool/Moderation.pm \
	Sympa/Spool/Task.pm \
	Sympa/Task.pm \
	Sympa/Template.pm \
	Sympa/Ticket.pm \
	Sympa/Tools/Data.pm \
	Sympa/Tools/DKIM.pm \
	Sympa/Tools/Domains.pm \
	Sympa/Tools/File.pm \
	Sympa/Tools/Password.pm \
	Sympa/Tools/SMIME.pm \
	Sympa/Tools/Text.pm \
	Sympa/Tools/Time.pm \
	Sympa/Topic.pm \
	Sympa/Tracking.pm \
	Sympa/Upgrade.pm \
	Sympa/User.pm \
	Sympa/WWW/Auth.pm \
	Sympa/WWW/Marc.pm \
	Sympa/WWW/Marc/Search.pm \
	Sympa/WWW/Report.pm \
	Sympa/WWW/SharedDocument.pm \
	Sympa/WWW/Session.pm \
	Sympa/WWW/SOAP.pm \
	Sympa/WWW/SOAP/Transport.pm \
	Sympa/WWW/Tools.pm

man3ext = 3Sympa
MAN3POD = \
	$(nobase_nodist_modules_DATA) \
	$(nobase_dist_modules_DATA) \
	$(nobase_modules_DATA)
man3_MANS =
noinst_DATA = stamp-man3

EXTRA_DIST = \
	Sympa/Constants.pm.in \
	Sympa/Internals.podpl \
	$(nobase_modules_DATA)

CLEANFILES = \
	Sympa/Constants.pm \
	Sympa/Internals.pod \
	stamp-man3T stamp-man3 *.$(man3ext)

Sympa/Constants.pm: Sympa/Constants.pm.in Makefile
	@[ -d Sympa ] || mkdir Sympa
	@rm -f $@
	$(AM_V_GEN)$(SED) \
		-e 's|--VERSION--|$(VERSION)|' \
		-e 's|--USER--|$(USER)|' \
		-e 's|--GROUP--|$(GROUP)|' \
		-e 's|--CONFIG--|$(CONFIG)|' \
		-e 's|--WWSCONFIG--|$(WWSCONFIG)|' \
		-e 's|--SENDMAIL_ALIASES--|$(SENDMAIL_ALIASES)|' \
		-e 's|--piddir--|$(piddir)|' \
		-e 's|--expldir--|$(expldir)|' \
		-e 's|--spooldir--|$(spooldir)|' \
		-e 's|--sysconfdir--|$(sysconfdir)|' \
		-e 's|--localedir--|$(localedir)|' \
		-e 's|--libexecdir--|$(libexecdir)|' \
		-e 's|--sbindir--|$(sbindir)|' \
		-e 's|--scriptdir--|$(scriptdir)|' \
		-e 's|--modulesdir--|$(modulesdir)|' \
		-e 's|--defaultdir--|$(defaultdir)|' \
		-e 's|--arcdir--|$(arcdir)|' \
		-e 's|--bouncedir--|$(bouncedir)|' \
		-e 's|--execcgidir--|$(execcgidir)|' \
		-e 's|--staticdir--|$(staticdir)|' \
		-e 's|--cssdir--|$(cssdir)|' \
		-e 's|--picturesdir--|$(picturesdir)|' \
		< $(srcdir)/$@.in > $@

Sympa/Internals.pod: Sympa/Internals.podpl Sympa/Constants.pm.in $(nobase_modules_DATA)
	@[ -d Sympa ] || mkdir Sympa
	@rm -f $@
	$(AM_V_GEN)$(PERL) $< Sympa/Constants.pm.in $(nobase_modules_DATA) > $@

stamp-man3: $(MAN3POD) Makefile
	@test -n "$(man3ext)" || exit 0; \
	rm -f *.$(man3ext); \
	for pm in $(MAN3POD); do \
		echo "$$pm" \
		| $(SED) -e 's/\.pm$$//' -e 's/\.pod$$//' -e 's/\//::/g' \
		| while read pod; do \
			rm -f $$pod.$(man3ext); \
			if test -f $(top_builddir)/src/lib/$$pm; then \
				pmfile=$(top_builddir)/src/lib/$$pm; \
			else \
				pmfile=$(top_srcdir)/src/lib/$$pm; \
			fi; \
			if grep '^=head1 NAME$$' $$pmfile > /dev/null; then \
				echo "  GEN   " $$pod.$(man3ext); \
				$(POD2MAN) --section=$(man3ext) \
					--name $$pod \
					--center="sympa $(VERSION)" \
					--lax --release="$(VERSION)" \
					$$pmfile $$pod.$(man3ext); \
			fi; \
		done; \
	done; \
	echo timestamp > stamp-man3T && mv stamp-man3T stamp-man3

install-data-hook: stamp-man3
	$(MKDIR_P) "$(DESTDIR)$(man3dir)"
	for file in *.$(man3ext); do \
		$(INSTALL_DATA) "$$file" "$(DESTDIR)$(man3dir)"; \
	done

uninstall-hook:
	cd "$(DESTDIR)$(man3dir)" && rm -f *.$(man3ext)

