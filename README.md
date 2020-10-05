# Ingress Maxfield (v4.0) - Modified version - WIP

## An [Ingress](https://ingress.com/) Linking and Fielding Strategy Generator
	
### Usage

Get information about the maxfield parameters via `maxfield-plan --help`:

```
usage: maxfield.py [-h] [--version] [-n NUM_AGENTS]
                   [--num_field_iterations NUM_FIELD_ITERATIONS] [-c NUM_CPUS]
                   [--max_route_solutions MAX_ROUTE_SOLUTIONS]
                   [--max_route_runtime MAX_ROUTE_RUNTIME] [-o OUTDIR]
                   [--skip_plots] [--skip_step_plots] [-r]
                   [--google_api_key GOOGLE_API_KEY]
                   [--google_api_secret GOOGLE_API_SECRET] [--output_csv] [-v]
				   [-ol] MAX_OUTGOING_LINKS
                   filename

Ingress Maxfield: An Ingress Linking and Fielding Strategy Generator.

positional arguments:
  filename              The properly formatted portal file.

optional arguments:
  -h, --help            show this help message and exit
  --version             show program's version number and exit
  -n NUM_AGENTS, --num_agents NUM_AGENTS
                        The number of agents in the operation. (default: 1)
  --num_field_iterations NUM_FIELD_ITERATIONS
                        The number of random field plans to generate before
                        selecting the best. (default: 1000)
  -c NUM_CPUS, --num_cpus NUM_CPUS
                        The number of CPUs used to generate field plans. If
                        <1, use maximum. (default: 1)
  --max_route_solutions MAX_ROUTE_SOLUTIONS
                        The maximum number of agent routes to generate before
                        selecting the best. (default: 1000)
  --max_route_runtime MAX_ROUTE_RUNTIME
                        The maximum runtime of the agent routing algorithm in
                        seconds. (default: 60)
  -o OUTDIR, --outdir OUTDIR
                        The directory where results are saved. Created if
                        necessary. (default: .)
  --skip_plots          Skip generating plots. (default: False)
  --skip_step_plots     Skip generating step-by-step linking plots. (default:
                        False)
  -r, --res_colors      Use Resistance color scheme. (default: False)
  --google_api_key GOOGLE_API_KEY
                        A Google Maps API key. If set, make plots on top of
                        Google Maps background. (default: None)
  --google_api_secret GOOGLE_API_SECRET
                        A Google Maps API signature secret. If not set, do not
                        use signature. (default: None)
  --output_csv          Output machine-readable CSV files. (default: False)
  -v, --verbose         Print information along the way. (default: False)
  -ol, --max_outgoing_links MAX_OUTGOING_LINKS
						The maximum number of outgoing links from a portal. (default: 8)
```

### Portal list format

TBD
		
### Issues and Contributing

Anyone is welcome to submit issues or contribute to the development
of Maxfield via [Github](https://github.com/tvwenger/maxfield).

### License and Warranty

GNU Public License
http://www.gnu.org/licenses/

Maxfield is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

Maxfield is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE. See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with Maxfield. If not, see http://www.gnu.org/licenses/
