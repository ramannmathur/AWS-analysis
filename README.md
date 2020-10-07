# AWS-spot price analysis using decision Tree

The recent improvement in the cloud computing model is
a spot instance market. Cloud service providers have to
efficiently distribute the resources to the customers without
violating the Service Level Agreement (SLA) made between
them. To accomplish the peak demand from clients and to
satisfy SLA, Cloud providers will over-cater their data
centres. EC2 and S3 of AWS represents Infrastructure as a
service product and through virtualization, large computing
resource can be dynamically assigned to customers demand.
Due to the dynamic nature of spot pricing, instances face out
of bid breakdown. Whenever a client requires service, they
buy those instances by paying a yearly fee. At times clients
will try to buy an on- demand instance at a higher hourly fee
without any assurance on instance performance at the given
time duration. Reserved and on-demand instances remain
active and work till the time the user cancels or terminates it.
Unused and free Elastic Compute (EC2) capacity is bid by
Amazon for less price than on demand cost [1]. Amazon
introduced this market to utilize its resources effectively.
Fluctuating pricing is the major factor of spot Instance. It
depends on the demand from the client’s end. Amazon
introduced spot instances to sell its spare services through
different pricing models based on their utility. The models
provide various assurances with respect to instances
regarding their starting or termination time. Spot requests are
made by clients at any time specifying the maximum hourly
bid price. Amazon runs three models to fix the spot price
like sealed bid, multi-unit and price market-driven auction. If
the spot price is less than the bid cost, users are given with
the spot instances.
