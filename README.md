Approval Build Tests
=====================

These tests are for the [Approval Tests](https://github.com/emilybache/ApprovalTests.Java) build. I use them while I am refactoring the build from using Ant to Maven.

First install [TextTest](http://texttest.org) then run:

	texttest -d $PWD -c $APPROVALS_CHECKOUT

where $PWD is the absolute path to the same folder as this README file, and $APPROVALS_CHECKOUT is the absolute path to where
Approvals.Java is checked out.
