noinst_LTLIBRARIES = libsystem_wrappers.la

noinst_HEADERS = include/aligned_array.h \
		 include/asm_defines.h

libsystem_wrappers_la_SOURCES = include/aligned_malloc.h \
				include/cpu_features_wrapper.h \
				include/event_wrapper.h \
				include/field_trial.h \
				include/file_wrapper.h \
				include/metrics.h \
				include/metrics_default.h \
				include/rw_lock_wrapper.h \
				include/sleep.h \
				source/aligned_malloc.cc \
				source/cpu_features.cc \
				source/event.cc \
				source/event_timer_posix.h \
				source/event_timer_win.h \
				source/file_impl.cc \
				source/metrics_default.cc \
				source/rw_lock.cc \
				source/rw_lock_posix.h \
				source/rw_lock_win.h \
				source/sleep.cc

EXTRA_DIST = BUILD.gn

if HAVE_POSIX
libsystem_wrappers_la_SOURCES += source/event_timer_posix.cc \
				 source/rw_lock_posix.cc
else
EXTRA_DIST += source/event_timer_posix.cc \
	      source/rw_lock_posix.cc
endif

if HAVE_WIN
libsystem_wrappers_la_SOURCES += source/event_timer_win.cc \
				 source/rw_lock_win.cc
else
EXTRA_DIST += source/event_timer_win.cc \
	      source/rw_lock_win.cc
endif

libsystem_wrappers_la_CXXFLAGS = $(AM_CXXFLAGS) $(COMMON_CXXFLAGS)
