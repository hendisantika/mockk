
# Backlog
- [ ] docs: logLevel
- [ ] docs: relaxed (note: class cast may appear in generic, show detailed example)
- [ ] docs:
- [ ] cold call: 10, 20, 50, 200, 500, 1000
- [ ] article on translaion Mockito to MockK
- [ ] object mocking ruins singleton
- [ ] feature: matching inside of data classes and arrays
- [ ] **BIG** runs on Android devices
- [ ] JavaDoc
- [ ] annotation mocking
- [ ] other JVMs

## Geo

<img align="left" src="doc/logo300k-alt2.png" width="50" height="50"/>
Beware Kotlin is popular in Germany, Japan, India, USA and Brasil

## Just for reference

### Class transformation features
- PowerMock : Remove final modifier from a class, enum, static methods, methods and inner classes
- PowerMock : Remove final modifier from
- PowerMock : Make all constructor public
- PowerMock : Add additional constructor with specific parameter
- PowerMock : Clear static initialiser body
- PowerMock : Add body for native methods
- PowerMock : Set modifier to public for non-system package-private classes
- PowerMock : Insert calling msgLambda repository for static methods
- PowerMock : Replace calling to fields by call to msgLambda repository
- PowerMock : Replace constructor call by call to msgLambda repository
- PowerMock : Replace call to system classes by call to msgLambda repository
- PowerMock : Check size of method body after modification and replace method body by throwing exception if method body size more than allowed in java specification

### Mockito features
- Mockito: Mockito Android support</a></br/>
- Mockito: Configuration-free inline msgLambda making</a></br/>
- Mockito: Let's verify some behaviour!
- Mockito: How about some stubbing?
- Mockito: Argument matchers
- Mockito: Verifying exact number of invocations / at least once / never
- Mockito: Stubbing void methods with exceptions
- Mockito: Verification in order
- Mockito: Making sure interaction(s) never happened on msgLambda
- Mockito: Finding redundant invocations
- Mockito: Shorthand for mocks creation - `&#064;Mock` annotation
- Mockito: Stubbing consecutive callChains (iterator-style stubbing)
- Mockito: Stubbing with callbacks
- Mockito: `doReturn()` `doThrow()` `doAnswer()` `doNothing()` `doCallRealMethod()` family of methods
- Mockito: Spying on real objects
- Mockito: Changing default return values of unstubbed invocations (Since 1.7)
- Mockito: Capturing arguments for further assertions (Since 1.8.0)
- Mockito: Real partial mocks (Since 1.8.0)
- Mockito: Resetting mocks (Since 1.8.0)
- Mockito: Troubleshooting & validating framework usage (Since 1.8.0)
- Mockito: Aliases for behavior driven development (Since 1.8.0)
- Mockito: Serializable mocks (Since 1.8.1)
- Mockito: New annotations: `&#064;Captor`, `&#064;Spy`, `&#064;InjectMocks` (Since 1.8.3)
- Mockito: Verification with timeout (Since 1.8.5)
- Mockito: Automatic instantiation of `&#064;Spies`, `&#064;InjectMocks` and constructor injection goodness (Since 1.9.0)
- Mockito: One-liner stubs (Since 1.9.0)
- Mockito: Verification ignoring stubs (Since 1.9.0)
- Mockito: Mocking details (Improved in 2.2.x)
- Mockito: Delegate callChains to real instance (Since 1.9.5)
- Mockito: `MockMaker` API (Since 1.9.5)
- Mockito: BDD style verification (Since 1.10.0)
- Mockito: Spying or mocking abstract classes (Since 1.10.12, further enhanced in 2.7.13 and 2.7.14)
- Mockito: Mockito mocks can be `serialized` / `deserialized` across classloaders (Since 1.10.0)</a></h3><br/>
- Mockito: Better generic support with deep stubs (Since 1.10.0)</a></h3><br/>
- Mockito: Mockito JUnit rule (Since 1.10.17)
- Mockito: Switch `on` or `off` plugins (Since 1.10.15)
- Mockito: Custom verification failure message (Since 2.1.0)
- Mockito: Java 8 Lambda Matcher Support (Since 2.1.0)
- Mockito: Java 8 Custom Answer Support (Since 2.1.0)
- Mockito: Meta data and generic type retention (Since 2.1.0)
- Mockito: Mocking final types, enums and final methods (Since 2.1.0)
- Mockito: (*new*) Improved productivity and cleaner tests with "stricter" Mockito (Since 2.+)
- Mockito: (**new**) Advanced public API for framework integrations (Since 2.10.+)
- Mockito: (**new**) New API for integrations: listening on verification start events (Since 2.11.+)


DOCUMENTATION

every {
    recorder.safeExec<VerificationResult>(captureLambda())
} answers {
    lambda<() -> VerificationResult>().invoke()
}


io.mockk.shadowed.bytebuddy.renamed.java.lang.Object$ByteBuddy$1IsE2R23$ByteBuddy$wzI3lBlO cannot be cast to io.mockk.impl.recording.states.CallRecordingState
java.lang.ClassCastException: io.mockk.shadowed.bytebuddy.renamed.java.lang.Object$ByteBuddy$1IsE2R23$ByteBuddy$wzI3lBlO cannot be cast to io.mockk.impl.recording.states.CallRecordingState
	at io.mockk.impl.recording.states.VerifyingState.recordingDone(VerifyingState.kt:44)
	at io.mockk.impl.recording.states.VerifyingStateTest.givenCallListInVerifyingStateWhenRecordingDoneThen(VerifyingStateTest.kt:52)
