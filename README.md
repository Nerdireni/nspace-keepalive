# nspace-keepalive
Keeps every Nspace platform alive. A GitHub Actions workflow pings each backend's health endpoint every 6 hours, so free Supabase projects never pause from inactivity (Supabase pauses free projects after 7 days with no activity).
Backends watched: nairaspace.com (gieiiofpdgdrsctsrfam), Nairaspace Hub (gieiiofpdgdrsctsrfam, pcxgmlptoninadehpbud), Nspacemail (rojatrsblzrcsarwhhlq), Nairaspace Mobile Application (ddhyfpoeznxsbfykobsh), Mindsight (pybhnhcdqajymsrskaae). It also pings the live sites: www.nairaspace.com, nairaspace-creator-hub.lovable.app, nspaceplus.nairaspace.com, amtacitizens.com, nspacemail.nairaspace.com, kruzcollection.com, emmaneagleeye.com.
Note: this keeps awake projects awake. It cannot wake a project that is already paused - resume that once first.
