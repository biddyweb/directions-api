[Go to overview](./README.md)

## What is one credit?

You can use [the estimator in the dashboard](https://graphhopper.com/dashboard/#/pricing) to easily calculate the necessary credits or get more details of how credits are calculated with the following:

 * one Routing API request costs 1 credit. Every 10 via-points will cost 1 additional credit. E.g. 11 via-points cost 2 credits
 * one Geocoding API request costs 1 credit
 * one Matrix API request with some start locations and some destinations costs `starts * destinations / 2` credits if `starts` or `destinations` are less than 20. For bigger matrices we use the cheaper formular `MAX_OF(starts, destinations) * 10`. For example you have 2 start locations and 10 destinations the charged credits are `2 * 10 / 2 = 10` or for 30 start and 40 destinations it is `40 * 10 = 400`
 * the costs for one Optimization API request depends on the number of vehicles and activities and is calculated as `vehicles * activities * 10`
  
## API credit limits

The API credit limits are listed in the dashboard and depend on the selected package. The limits are also reported in the response header for every request.

## Pricing

You can find the detailed pricing in the dashboard. For individual requirements we offer small and big custom packages.

## Can I pay on demand?

It is possible to pay online without delay. But paying for an increased demand is currently not possible, please [let us know](https://graphhopper.com/#contact) of your needs and we can arrange a solution.

## Do you offer discounts?

Yes, you get a discount if you sign up for an annually contract. Also [follow us on Twitter](https://twitter.com/graphhopper) to get the latest campaign.

## How to cancel, upgrade or downgrad my package?

Please [contact us](https://graphhopper.com/#contact)
