# REDIS AE_EVENT LOOP

## File `ae.h`

### Loop Event
*  `aeEventLoop`

    ![123](1.png)

* `aeBeforeSleepProc` => before & after hook

### Basic Event

* `aeFileEvent` => `aeFileProc` => read & write

* `aeTimeEvent` => `aeTimeEvent` & `aeFinalizerProc`

* `aeFiredEvent`


### Methods:
![methods](./png/3.png)


## File: `ae_epoll.c`

### Methods:

![methods](./png/2.png)


* `aeApiCreate()`

* `aeApiResize()`

* `aeApiFree()`

* `aeApiAddEvent()`

* `aeApiDelEvent()`

* `aeApiPoll()`

* `aeApiName()`

