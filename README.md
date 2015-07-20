# Minimal GTK2 based daemon/consumer for FDO compliant desktop notifications

Spec: http://developer.gnome.org/notification-spec/

Test suite compliance:

	test-action-icons:       0% Action icons not supported
	test-basic:            100% OK (long notifications are cut -- not strictly specification compliant, but acceptable in most cases)
	test-default-action:   100% OK
	test-error:            100% OK (since the test doesn't do anything but showing a notification)
	test-image:             50% stock OK, URI not supported
	test-markup:           100% OK
	test-multiple-actions: 100% OK
	test-persistence:        0% Persistence not supported
	test-removal:          100% OK
	test-replace:          100% OK
	test-replace-widget:   100% OK
	test-resident:           0% Persistence not supported
	test-rtl:              100% OK
	test-server-info:      100% OK
	test-size-change:        0% other notifications not adjusted for new size
	test-transient:       (100%) Persistence not supported, therefore automatically transient
	test-urgency:            0% Urgency not supported
	test-xy                100%
	test-xy-actions:       100%
	text-xy-stress:        100%
	total:                  73%

© Samuel Vincent Creshal <samuel@creshal.de> 2011-2015

# License

*(TL;DR: 2-clause MIT)*

Redistribution and use in source and binary forms, with or without
modification, are permitted provided that the following conditions are met:

1. Redistributions of source code must retain the above copyright notice, this
list of conditions and the following disclaimer.

2. Redistributions in binary form must reproduce the above copyright notice,
this list of conditions and the following disclaimer in the documentation
and/or other materials provided with the distribution.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE
ARE DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE
LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR
CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF
SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS
INTERRUPTION) HOWEVER CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN
CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE)
ARISING IN ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.

