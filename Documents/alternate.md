## 1. Conforming Alternate Version and Non-Interference

The Conforming Alternate Version Test Conditions deviate slightly from the remaining tests in a few important ways:

-   The Conforming Alternate Version Test Conditions are presented first because identifying conforming accessible alternate versions of content helps define the scope of testing. Non-conforming content that has a conforming alternate version is tested for interference and then excluded from testing after this test.

-   While it is important to identify conforming alternate versions to define the test scope, it will not be possible to determine if a conforming alternate version was provided until all other applicable tests are completed. (It cannot be a conforming alternate version if it does not pass all applicable Test Conditions.)

-   The results for Conforming Alternate Version Test Conditions do not follow the **TRUE=PASS, FALSE=FAIL, DOES NOT APPLY (DNA)** pattern that the rest of the Test Conditions follow. Providing a conforming alternate version is not a requirement. Rather, it is an acceptable method to provide the same information and/or functionality in an accessible manner when other non-conforming version(s) of that content exist. Therefore, **FAIL** is not an appropriate test result. When a Test Condition is **TRUE**, the Test Condition result is **PASS**. If a Test Condition is **FALSE**, a conforming alternate version does not exist and the Test Condition result is **DOES NOT APPLY**.

### Alternate Version Accessibility

#### Identify Content

Identify multiple versions of the same content, i.e. content that has been provided in more than one way and with the explicit or implicit intent that one or more is provided as an accessible alternative.

1.  Alternate versions may be provided for a part of the page, entire pages, or an entire site.

2.  Various methods may indicate that an alternate version is available, including:

    -   Instructions that describe how to enable accessibility

    -   Content is identified as the accessible version

    -   Multiple methods are provided to complete a task (e.g. a calendar widget and a text field are provided for a user to enter a date)

    -   A link’s destination is an accessible alternate version or a version for assistive technology (e.g. screen reader version)

    -   User preferences or settings to enable accessibility

    -   User controls to modify colors and text appearance

3.  The alternate version(s) does not need to reside within the scope of conformance, or even on the same web site, as long as it is as freely available as the non-conforming version. For this test process, scope of testing is limited to alternatives that are available on a desktop computer. Alternate versions do not include mobile applications that can only be accessed on a mobile device.

If there is only one version of content, the result for the following test ID(s) is **DOES NOT APPLY**: 1.A to 1.E.

#### Check alt-version-conformant

| Test Name              | Test ID | Test Condition                                                                                                              |
|------------------------|---------|-----------------------------------------------------------------------------------------------------------------------------|
| alt-version-conformant | 1.A     | <span id="OLE_LINK2" class="anchor"></span>An alternate version passes all applicable Test Conditions in this test process. |

##### Applicability:

This Test Condition **DOES NOT APPLY (DNA)** if there is only one version of content.

##### How to Test:

1.  Enable accessibility with site settings if provided.

2.  If one of the versions has been identified for accessibility purposes, consider that the alternate version and provide test results for only that version in this Test ID.

3.  Following this test process, test the identified “accessible” version for all applicable Test Conditions.

    1.  It may be necessary to perform extensive testing before a result for this Test Condition can be found. If user settings are provided to enable accessibility for the entire site, the entire site is the alternate version, and the entire site must pass all Test Conditions.

    2.  If a failure is found in the identified ‘accessible’ version, enter FAIL for the appropriate Test ID. It is not necessary to continue testing for this test (ID 1.A) after a failure has been found. Evaluate results.

    3.  If none of the versions is identified for accessibility, test all versions until a version that passes all applicable Test Conditions is found.

        1.  If a failure is found in a version, stop testing that version and test the other version(s).

##### Evaluate Results: 

If the following is **TRUE**, then the content **PASSES**; if the following is **FALSE**, then this Test Condition **DOES NOT APPLY** **(DNA)**:

1.  There is an accessible alternate version of content that passes all applicable Test Conditions in this test process.

If the result of this test condition is:

-   **PASSES**, continue to 1.B. The accessible alternate version (that passed this 1.A. test) will be referred to as the “accessible version” in subsequent tests.

-   **DOES NOT APPLY (DNA)**, mark the results for the remaining Conforming Alternate Version Test Conditions (1.B - 1.E) as **DOES NOT APPLY (DNA)** and continue testing all versions with subsequent test conditions. All versions of the content should be tested and included in the test report.

###### Note:

-   Alternate versions may be provided to accommodate different technology environments or user groups. At least one version would need to pass all Test Conditions.

-   It may be helpful to review product documentation for information about accessible versions or enabling accessibility.

-   While testing for the Alternate Version Test Conditions may halt when the identified “accessible” version has a failed Test Condition, further testing of the version may be necessary to complete the other tests in this test process. When there is no conforming alternative, all versions of the content should be tested and included in the test report.

#### Check alt-version-equivalent

| Test Name              | Test ID | Test Condition                                                                    |
|------------------------|---------|-----------------------------------------------------------------------------------|
| alt-version-equivalent | 1.B     | The accessible version is up to date with the same information and functionality. |

##### Applicability:

This Test Condition **DOES NOT APPLY** if Test ID 1.A was evaluated as **DOES NOT APPLY** **(DNA)**.

##### How to Test:

1.  Continue from Test 1.A.

2.  Review the content of the non-conforming version.

3.  Compare the accessible version (that passed Test 1.A) with the non-conforming version for equivalence (i.e., equivalent information and functionality).

##### Evaluate Results: 

If the following is **TRUE**, then the content **PASSES.** If the following is **FALSE**, then this Test Condition **DOES NOT APPLY** **(DNA)**:

1.  The accessible version (that passed 1.A) provides all of the same information and functionality in the same human language as the non-conforming content.

If the result of this test condition is:

-   **PASSES**, continue to 1.C.

-   **DOES NOT APPLY (DNA),** mark 1.C - 1.E as **DOES NOT APPLY (DNA)** and continue testing all versions with subsequent test conditions. All versions of the content should be tested and included in the test report.

###### Note:

-   The accessible version does not need to be matched page for page with the original (e.g., the accessible version may consist of more or fewer pages).

-   While testing for the Alternate Version Test Conditions may halt when the identified “accessible” version has a failed Test Condition, further testing of the version may be necessary to complete the other tests in this test process. When there is no conforming alternative, all versions of the content should be tested and included in the test report.

### Access to the Accessible Alternate Version

#### Identify Content

A page with the non-conforming version of the content that also provides a mechanism, method, or path for the user to reach the proposed accessible equivalent version of the content. **CS: can continue testing**

Various methods may be used to reach an alternate version, including:

-   A link to an accessible alternate version or a version for assistive technology (e.g. screen reader version)

-   User preferences or settings to enable accessibility for a page or the entire site

-   User controls to modify colors and text appearance of the page or entire site

-   The accessible equivalent version is on the same page as the non-conforming version.

If the test result for 1.A or 1.B is **DOES NOT APPLY**, the result for the following test ID(s) is **DOES NOT APPLY**: 1.C to 1.E.

**Note**: Only ONE method can be used to present an alternate, accessible version of content. Either

-   the user first encounters the non-conforming content and must navigate to accessible alternate version (tested in 1.C) OR

-   the user is presented with the conforming version of content first (skip to test 1.D). **CS: does this mean the same thing?**

> Either 1.C or 1.D must PASS; both do not apply simultaneously to the same accessible equivalent version.

#### Check alt-version-access

| Test Name          | Test ID | Test Condition                                                                                                                                                                             |
|--------------------|---------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| alt-version-access | 1.C     | <span id="OLE_LINK5" class="anchor"><span id="OLE_LINK6" class="anchor"></span></span>The mechanism to reach the proposed accessible  version from the non-conforming page is accessible. |

##### Applicability:

This Test Condition **DOES NOT APPLY** if there is only one version of content, or if the user is presented with the conforming version of content first (move to test 1.D).

##### How to Test:

1.  Continue from Test 1.B.

2.  Identify the mechanism used to reach the proposed accessible equivalent version.

    1.  If necessary, go back to the page that provided the mechanism to select or enable the proposed accessible version.

    2.  This may be a link or some function that is on a non-conforming page

    3.  This may be user settings or preferences.

3.  Following this test process, test the mechanism for all applicable Test Conditions.

##### Evaluate Results: 

If the following is **TRUE**, then the content **PASSES.** If the following is **FALSE**, then this Test Condition **FAILS**:

1.  The mechanism used to reach the proposed accessible equivalent version passes all applicable Test Conditions.

Either test condition 1.C OR 1.D must **PASS** for a proposed conforming alternate version. If the result of test condition 1.C is:

-   **PASSES**, mark 1.D as **DOES NOT APPLY (DNA)**, continue testing 1.E.

<!-- -->


###### Note:

-   Applicable mechanism tests may include Links and Buttons, Headings, Forms, and/or other tests.

-   The mechanism to access the conforming version should directly or indirectly indicate that it leads to the accessible version. For example, text preceding a link to the accessible version might directly state that the link leads to the accessible version. It may also be possible to “hide” non-conforming content from AT and/or exclude it from keyboard focus, thereby limiting access only to the accessible version for users with disabilities. Such an approach, however, may not be possible, depending on the content.

-   The mechanism may be explicitly provided in the content or may be relied upon to be provided by either the platform or by user agents, including assistive technologies.

-   The mechanism needs to meet all success criteria for the conformance level claimed.

#### Identify Content

Identify all mechanisms, methods, and paths for a user to reach the non-conforming version(s) of the content.

If the test result for 1.A or 1.B is **DOES NOT APPLY**, the result for the following test IDs is **DOES NOT APPLY**: 1.C to 1.E. If the test result for 1.C is PASS, the result for the following test ID is **DOES NOT APPLY**: 1.D.

### Access to the Non-Conforming Version 

#### Check alt-version-nc-access

| Test Name             | Test ID | Test Condition                                                                                                        |
|-----------------------|---------|-----------------------------------------------------------------------------------------------------------------------|
| alt-version-nc-access | 1.D     | <span id="OLE_LINK8" class="anchor"></span>The non-conforming version(s) can only be reached from conforming content. |

##### Applicability:

This Test Condition **DOES NOT APPLY** if:

-   there is only one version of the content, OR

-   Test ID 1.A or 1.B was evaluated as **DOES NOT APPLY (DNA)**, OR

-   Test ID 1.C was evaluated as **PASSES.**

##### How to Test:

1.  Identify how the non-conforming version(s) of the content can be accessed

    1.  The non-conforming version can only be accessed from the accessible equivalent version.

    2.  Both the accessible equivalent version and the non-conforming version are accessed from another page.

        1.  Does the page providing access conform to all applicable test processes?

        2.  Is there another way to access the non-conforming version?

##### Evaluate Results: 

If any of the following is **TRUE**, then the content **PASSES.** if the following are all **FALSE**, then this Test Condition **DOES NOT APPLY** **(DNA)**:

1.  The non-conforming version can only be reached from the accessible equivalent version (that passed Test ID 1.B), OR

2.  The non-conforming version can only be reached from a page that:

    1.  passes all other Test Conditions AND

    2.  also provides a mechanism to reach the accessible equivalent version (that passed Test ID 1.A and 1.B)

Either test condition 1.C OR 1.D must **PASS** for a conforming alternate version to exist. If the result of this test condition is:

-   **PASSES**, continue testing 1.E.

-   **DOES NOT APPLY (DNA)** AND you marked 1.C as **PASSES,** continue testing 1.E.

-   **DOES NOT APPLY (DNA)** AND you marked 1.C as **DOES NOT APPLY (DNA),** mark 1.E as **DOES NOT APPLY (DNA)** and continue testing all versions with subsequent test conditions.

###### Note:

-   For Evaluate results step 2 above to be **TRUE**, both the page and mechanism must pass all applicable Test Conditions. Following this test process, test the page and mechanism for all applicable Test Conditions.

### Non-Interference

#### Identify Content

The non-conforming version(s) of the content that has a conforming alternate version.

If the test results for both 1.C and 1.D are **DOES NOT APPLY**, the result for the following test ID is **DOES NOT APPLY**: 1.E.

#### Check non-interference

| Test Name        | Test ID | Test Condition                                                            |
|------------------|---------|---------------------------------------------------------------------------|
| non-interference | 1.E     | Content in the non-conforming version(s) meets Conformance Requirement 5. |

##### Applicability:

This Test Condition **DOES NOT APPLY** if:

-   there is only one version of the content, OR

-   Test ID 1.C AND 1.D were evaluated as **DOES NOT APPLY (DNA).**

##### How to Test:

1.  The non-conforming content that has a conforming alternate version must be tested prior to omitting the content from the rest of testing.

2.  If necessary and/or applicable, disable accessibility features within site setting or preferences.

3.  Following this test process, complete ONLY the following tests on the non-conforming version(s) of the content:

    1.  Test ID 2.A (1.4.2-audio-control)

    2.  Test ID 2.B (2.2.2-blinking-moving-scrolling)

    3.  Test ID 2.C (2.2.2-auto-updating)

    4.  Test ID 3.A (2.3.1-flashing)

    5.  Test ID 4.C (2.1.2-no-keyboard-trap)

4.  Mark the appropriate Test ID where any of the tests above produces a result of **FAIL** or **NOT TESTED** (for Test ID 3.A).

##### Evaluate Results: 

If the following is **TRUE**, then the content **PASSES.** If the following is **FALSE**, then this Test Condition **FAILS:**

1.  The results for each of the following tests are PASS or DOES NOT APPLY for the non-conforming version(s) of the content.

    1.  Test ID 2.A (1.4.2-audio-control)

    2.  Test ID 2.B (2.2.2-blinking-moving-scrolling)

    3.  Test ID 2.C (2.2.2-auto-updating)

    4.  Test ID 3.A (2.3.1-flashing)

    5.  Test ID 4.C (2.1.2-no-keyboard-trap)

**Note:** After performing this test on the non-conforming version of content that has a conforming alternate version for the content, omit testing of the non-conforming content from the rest of testing.

### Applicable Standards

| Section 508/WCAG Success Criteria                                                                                                                                                                                                                                                                                                                                                                                                                     | Baseline Requirements                                                                                                     |
|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------|
| [Conforming alternate version](https://www.w3.org/TR/WCAG20/#conforming-alternate-versiondef) is not a requirement. Conformance requirement \#1 allows non-conforming pages to be included within the scope of conformance as long as they have a "conforming alternate version". This ensures that all of the information and all of the functionality that is on the pages inside of the scope of conformance is available on conforming Web pages. | [20. Conforming Alternate Versions](https://section508coordinators.github.io/ICTTestingBaseline/20AlternateVersions.html) |
| [WCAG Conformance Requirement 5. Non-Interference](https://www.w3.org/TR/WCAG20/#conformance-reqs): The following success criteria apply to all content on the page, including content that is not otherwise relied upon to meet conformance, because failure to meet them could interfere with any use of the page:<br><ul><li>1.4.2 - Audio Control,</li><li>2.1.2 - No Keyboard Trap,</li><li>2.3.1 - Three Flashes or Below Threshold, and</li><li>2.2.2 - Pause, Stop, Hide.</li>| [25. Non-Interference](https://section508coordinators.github.io/ICTTestingBaseline/25Noninterference.html)                |

-------------------------------------------------
[Home/Table of Contents](index.md)    |    [Next -- 2. Auto-Playing and Auto-Updating Content](auto.md)
