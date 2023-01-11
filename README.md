# MES - Manufacturing Execution System

* MES is not a *thing* - there is not "MES" software.
* MES lives between ERP and SCADA
* MES needs to deliver on 4 things:
  - Work orders - a work order should == a production run for example
  - Scheduler - schedule work order
  - Overall equipment effectiveness ([MoreInfoHere][OEE-VID])  -- Availability, quality, performance
    * Efficiency are assets, areas
    * How are we running?
  - Downtime tracking

## MES will **always** have
  - Downtime tracking
  - OEE
  - Dashboards

**The problem** - when someone says I want MES - they are never talking about the same thing.
Often - scheduling is handled in ERP
Work orders may be manufacturing orders that are consumed from ERP
OEE and DT are always in MES

Other capabilities:
* Recipe management  -- Def - spec - deviation
* Digital quality inspection plans
* Sample collection (quality)
* SPC - statistical process control
* 9001 compliance
* Document management
* From BOM to inventory management
  - Consuming wip and raw
  - creating wip and raw

## Some example use-cases to solve for
* Want to improve recipe management
* Want to improve inspection/quality - paper driven process, need to digitize
* Digital work instructions

[OEE-VID]: https://www.youtube.com/watch?v=cFCtT71be40
