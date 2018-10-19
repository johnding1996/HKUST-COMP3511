# NOTE: this is a GNU Makefile.  You must use "gmake" rather than "make".
#
# Makefile for the threads assignment.  The threads assignment must
#  be done first!
#
# Copyright (c) 1992 The Regents of the University of California.
# All rights reserved.  See copyright.h for copyright notice and limitation 
# of liability and disclaimer of warranty provisions.

DEFINES = -DTHREADS
INCPATH = -I. -I../machine
HFILES = $(THREAD_H) 
CFILES = $(THREAD_C) 
C_OFILES = $(THREAD_O)


include ../Makefile.common
include ../Makefile.dep
#-----------------------------------------------------------------
# DO NOT DELETE THIS LINE -- make depend uses it
# DEPENDENCIES MUST END AT END OF FILE
main.o: ../threads/main.cc copyright.h utility.h ../machine/sysdep.h \
  /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h system.h \
  thread.h list.h list.cc scheduler.h ../machine/timer.h \
  ../machine/interrupt.h ../machine/stats.h
scheduler.o: ../threads/scheduler.cc copyright.h scheduler.h list.h \
  utility.h ../machine/sysdep.h /usr/include/stdio.h \
  /usr/include/sys/cdefs.h /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.cc \
  thread.h ../machine/timer.h system.h ../machine/interrupt.h \
  ../machine/stats.h
synch.o: ../threads/synch.cc copyright.h synch.h thread.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.h \
  list.cc system.h scheduler.h ../machine/timer.h ../machine/interrupt.h \
  ../machine/stats.h
system.o: ../threads/system.cc copyright.h system.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h thread.h \
  list.h list.cc scheduler.h ../machine/timer.h ../machine/interrupt.h \
  ../machine/stats.h
thread.o: ../threads/thread.cc copyright.h thread.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.h \
  list.cc switch.h synch.h system.h scheduler.h ../machine/timer.h \
  ../machine/interrupt.h ../machine/stats.h
utility.o: ../threads/utility.cc copyright.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h \
  /Library/Developer/CommandLineTools/usr/bin/../lib/clang/7.3.0/include/stdarg.h
interrupt.o: ../machine/interrupt.cc copyright.h ../machine/interrupt.h \
  list.h utility.h ../machine/sysdep.h /usr/include/stdio.h \
  /usr/include/sys/cdefs.h /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.cc \
  system.h thread.h scheduler.h ../machine/timer.h ../machine/stats.h
sysdep.o: ../machine/sysdep.cc copyright.h /usr/include/stdio.h \
  /usr/include/sys/cdefs.h /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h \
  /usr/include/signal.h /usr/include/sys/signal.h \
  /usr/include/sys/appleapiopts.h /usr/include/machine/signal.h \
  /usr/include/i386/signal.h /usr/include/machine/_mcontext.h \
  /usr/include/i386/_mcontext.h /usr/include/mach/i386/_structs.h \
  /usr/include/sys/_pthread/_pthread_attr_t.h \
  /usr/include/sys/_types/_sigaltstack.h \
  /usr/include/sys/_types/_ucontext.h /usr/include/sys/_types/_pid_t.h \
  /usr/include/sys/_types/_sigset_t.h /usr/include/sys/_types/_uid_t.h \
  /usr/include/sys/_pthread/_pthread_t.h /usr/include/sys/types.h \
  /usr/include/machine/types.h /usr/include/i386/types.h \
  /usr/include/sys/_types/_int8_t.h /usr/include/sys/_types/_int16_t.h \
  /usr/include/sys/_types/_int32_t.h /usr/include/sys/_types/_int64_t.h \
  /usr/include/sys/_types/_intptr_t.h \
  /usr/include/sys/_types/_uintptr_t.h /usr/include/machine/endian.h \
  /usr/include/i386/endian.h /usr/include/sys/_endian.h \
  /usr/include/libkern/_OSByteOrder.h \
  /usr/include/libkern/i386/_OSByteOrder.h \
  /usr/include/sys/_types/_dev_t.h /usr/include/sys/_types/_blkcnt_t.h \
  /usr/include/sys/_types/_blksize_t.h /usr/include/sys/_types/_gid_t.h \
  /usr/include/sys/_types/_in_addr_t.h \
  /usr/include/sys/_types/_in_port_t.h /usr/include/sys/_types/_ino_t.h \
  /usr/include/sys/_types/_ino64_t.h /usr/include/sys/_types/_key_t.h \
  /usr/include/sys/_types/_mode_t.h /usr/include/sys/_types/_nlink_t.h \
  /usr/include/sys/_types/_id_t.h /usr/include/sys/_types/_clock_t.h \
  /usr/include/sys/_types/_time_t.h \
  /usr/include/sys/_types/_useconds_t.h \
  /usr/include/sys/_types/_suseconds_t.h \
  /usr/include/sys/_types/_fd_def.h \
  /usr/include/sys/_types/_fd_setsize.h \
  /usr/include/sys/_types/_fd_set.h /usr/include/sys/_types/_fd_clr.h \
  /usr/include/sys/_types/_fd_zero.h /usr/include/sys/_types/_fd_isset.h \
  /usr/include/sys/_types/_fd_copy.h \
  /usr/include/sys/_pthread/_pthread_cond_t.h \
  /usr/include/sys/_pthread/_pthread_condattr_t.h \
  /usr/include/sys/_pthread/_pthread_mutex_t.h \
  /usr/include/sys/_pthread/_pthread_mutexattr_t.h \
  /usr/include/sys/_pthread/_pthread_once_t.h \
  /usr/include/sys/_pthread/_pthread_rwlock_t.h \
  /usr/include/sys/_pthread/_pthread_rwlockattr_t.h \
  /usr/include/sys/_pthread/_pthread_key_t.h \
  /usr/include/sys/_types/_fsblkcnt_t.h \
  /usr/include/sys/_types/_fsfilcnt_t.h /usr/include/sys/time.h \
  /usr/include/sys/_types/_timespec.h /usr/include/sys/_types/_timeval.h \
  /usr/include/sys/_types/_timeval64.h /usr/include/time.h \
  /usr/include/sys/_select.h /usr/include/sys/socket.h \
  /usr/include/machine/_param.h /usr/include/i386/_param.h \
  /usr/include/sys/_types/_sa_family_t.h \
  /usr/include/sys/_types/_socklen_t.h \
  /usr/include/sys/_types/_iovec_t.h /usr/include/errno.h \
  /usr/include/sys/errno.h /usr/include/sys/file.h \
  /usr/include/sys/fcntl.h /usr/include/sys/_types/_o_sync.h \
  /usr/include/sys/_types/_o_dsync.h /usr/include/sys/_types/_seek_set.h \
  /usr/include/sys/_types/_s_ifmt.h /usr/include/sys/_types/_filesec_t.h \
  /usr/include/sys/unistd.h /usr/include/sys/_types/_posix_vdisable.h \
  /usr/include/_types/_uint64_t.h /usr/include/sys/queue.h \
  /usr/include/sys/un.h /usr/include/sys/mman.h /usr/include/fcntl.h \
  ../machine/interrupt.h list.h utility.h ../machine/sysdep.h list.cc \
  system.h thread.h scheduler.h ../machine/timer.h ../machine/stats.h
stats.o: ../machine/stats.cc copyright.h utility.h ../machine/sysdep.h \
  /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h \
  ../machine/stats.h
timer.o: ../machine/timer.cc copyright.h ../machine/timer.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h system.h \
  thread.h list.h list.cc scheduler.h ../machine/interrupt.h \
  ../machine/stats.h
threadtest.o: ../threads/threadtest.cc /usr/include/string.h \
  /usr/include/_types.h /usr/include/sys/_types.h \
  /usr/include/sys/cdefs.h /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/Availability.h /usr/include/AvailabilityInternal.h \
  /usr/include/sys/_types/_size_t.h /usr/include/sys/_types/_null.h \
  /usr/include/sys/_types/_rsize_t.h /usr/include/sys/_types/_errno_t.h \
  /usr/include/sys/_types/_ssize_t.h /usr/include/strings.h \
  /usr/include/stdio.h /usr/include/sys/_types/_va_list.h \
  /usr/include/sys/stdio.h /usr/include/sys/_types/_off_t.h system.h \
  copyright.h utility.h ../machine/sysdep.h thread.h list.h list.cc \
  scheduler.h ../machine/timer.h ../machine/interrupt.h \
  ../machine/stats.h synch.h testcase.h
test.0.o: ../threads/test.0.cc list.h copyright.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.cc \
  system.h thread.h scheduler.h ../machine/timer.h \
  ../machine/interrupt.h ../machine/stats.h synch.h testcase.h
test.1.o: ../threads/test.1.cc system.h copyright.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h thread.h \
  list.h list.cc scheduler.h ../machine/timer.h ../machine/interrupt.h \
  ../machine/stats.h synch.h testcase.h
test.2.o: ../threads/test.2.cc list.h copyright.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.cc \
  system.h thread.h scheduler.h ../machine/timer.h \
  ../machine/interrupt.h ../machine/stats.h synch.h testcase.h
project1.o: ../threads/project1.cc list.h copyright.h utility.h \
  ../machine/sysdep.h /usr/include/stdio.h /usr/include/sys/cdefs.h \
  /usr/include/sys/_symbol_aliasing.h \
  /usr/include/sys/_posix_availability.h /usr/include/Availability.h \
  /usr/include/AvailabilityInternal.h /usr/include/_types.h \
  /usr/include/sys/_types.h /usr/include/machine/_types.h \
  /usr/include/i386/_types.h /usr/include/sys/_pthread/_pthread_types.h \
  /usr/include/sys/_types/_va_list.h /usr/include/sys/_types/_size_t.h \
  /usr/include/sys/_types/_null.h /usr/include/sys/stdio.h \
  /usr/include/sys/_types/_off_t.h /usr/include/sys/_types/_ssize_t.h \
  /usr/include/string.h /usr/include/sys/_types/_rsize_t.h \
  /usr/include/sys/_types/_errno_t.h /usr/include/strings.h list.cc \
  system.h thread.h scheduler.h ../machine/timer.h \
  ../machine/interrupt.h ../machine/stats.h synch.h testcase.h \
  /usr/include/unistd.h /usr/include/sys/unistd.h \
  /usr/include/sys/_types/_posix_vdisable.h \
  /usr/include/sys/_types/_seek_set.h /usr/include/_types/_uint64_t.h \
  /usr/include/sys/_types/_uid_t.h /usr/include/sys/_types/_gid_t.h \
  /usr/include/sys/_types/_intptr_t.h /usr/include/sys/_types/_pid_t.h \
  /usr/include/sys/_types/_useconds_t.h /usr/include/sys/select.h \
  /usr/include/sys/appleapiopts.h /usr/include/sys/_types/_fd_def.h \
  /usr/include/sys/_types/_timespec.h /usr/include/sys/_types/_timeval.h \
  /usr/include/sys/_types/_time_t.h \
  /usr/include/sys/_types/_suseconds_t.h \
  /usr/include/sys/_types/_sigset_t.h \
  /usr/include/sys/_types/_fd_setsize.h \
  /usr/include/sys/_types/_fd_set.h /usr/include/sys/_types/_fd_clr.h \
  /usr/include/sys/_types/_fd_isset.h /usr/include/sys/_types/_fd_zero.h \
  /usr/include/sys/_types/_fd_copy.h /usr/include/sys/_select.h \
  /usr/include/sys/_types/_dev_t.h /usr/include/sys/_types/_mode_t.h \
  /usr/include/sys/_types/_uuid_t.h /usr/include/gethostuuid.h
# DEPENDENCIES MUST END AT END OF FILE
# IF YOU PUT STUFF HERE IT WILL GO AWAY
# see make depend above
