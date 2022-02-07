# Divine Intervention
Adds some features for use within mixins

## Injectors
### ModifyOperand
Takes the topmost value on the operand stack and passes it to a handler method,
optionally also capturing the target method arguments, and replaces it with the
handler method's return value.

### EnumInject
A slightly weird injector that adds a constant to an enum. See [EnumInject.md](EnumInject.md) for an example.

## Installation
build.gradle:
```groovy
repositories {
    maven { url 'https://jitpack.io' }
}

dependencies {
    modImplementation "com.github.devs-immortal:Divine-Intervention:${project.divine_intervention_version}"
    annotationProcessor "com.github.devs-immortal:Divine-Intervention:${project.divine_intervention_version}"
}
```
gradle.properties:
```properties
# Dependencies
	divine_intervention_version = 0.2.2
```
