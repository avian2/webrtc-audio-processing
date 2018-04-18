noinst_LTLIBRARIES = librtc_base.la

noinst_HEADERS = arraysize.h \
		 atomicops.h \
		 basictypes.h \
		 constructormagic.h \
		 deprecation.h \
		 function_view.h \
		 gtest_prod_util.h \
		 ignore_wundef.h \
		 protobuf_utils.h \
		 numerics/safe_conversions.h \
		 numerics/safe_conversions_impl.h \
		 sanitizer.h \
		 swap_queue.h \
		 template_util.h \
		 thread_annotations.h \
		 trace_event.h \
		 type_traits.h

librtc_base_la_SOURCES = compile_assert_c.h \
		     criticalsection.cc \
		     criticalsection.h \
		     checks.cc \
		     checks.h \
		     event.cc \
		     event.h \
		     event_tracer.cc \
		     event_tracer.h \
		     logging.cc \
		     logging.h \
		     numerics/safe_minmax.h \
		     platform_thread.cc \
		     platform_thread.h \
		     platform_thread_types.cc \
		     platform_thread_types.h \
		     platform_file.cc \
		     platform_file.h \
		     race_checker.cc \
		     race_checker.h \
		     refcounter.h \
		     refcountedobject.h \
		     stringencode.cc \
		     stringencode.h \
		     stringutils.cc \
		     stringutils.h \
		     strings/string_builder.cc \
		     strings/string_builder.h \
		     thread_checker.h \
		     thread_checker_impl.cc \
		     thread_checker_impl.h \
		     timeutils.cc \
		     timeutils.h

librtc_base_la_CXXFLAGS = $(AM_CXXFLAGS) $(COMMON_CXXFLAGS)


EXTRA_DIST = BUILD.gn
