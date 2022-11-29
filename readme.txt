DayZ Toxic NWAF North West Airfield json Mod Changelog & Terms Of Use

Limited Testing on PC Chernarus Local Server DAYZ Version 1.19 Nov 2022.

Created by @scalespeeder. Please report bugs & errors to scalespeeder@gmail.com with screenshots.

TERMS OF USE
THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS
OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN
AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH
THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Using these modded files or snippets could break the functioning of your DAYZ server, requiring a reinstall that would wipe
all player progress.

Using these modded files or snippets neccessitates increased regular restarts to prevent server crashing.

It is suggested you thoroughly test your server after applying these files to ensure proper
functioning of your server.

This code snippet will spawn in a a number of permanent Toxic Gas Clouds at the NWAF North West Airfield

To install these snippets simply insert the whole code snippet into the correct position (near the top on a line after the first [ Bracket)
 in your cfgEffectArea.json file, save, reupload and restart your server.
 
 { 	"AreaName": "NWAF-SW", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4570, 0, 9598 ],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 10,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 50, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
        { 	"AreaName": "NWAF-SE",
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 5237, 0, 9814],
				"Radius": 100,
				"PosHeight": 26,
				"NegHeight": 10,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 50, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
        { 	"AreaName": "NWAF-E", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4732, 0, 10311],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 2,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 60, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
	 { 	"AreaName": "NWAF-W", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4145, 0, 10404],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 2,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 60, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
		{ 	"AreaName": "NWAF-Tower", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4471, 0, 10816],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 2,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 60, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
		{ 	"AreaName": "NWAF-Tents", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4205, 0, 11032],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 2,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 60, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
		
			{ 	"AreaName": "NWAF-N-Barracks", 
			"Type": "ContaminatedArea_Static", 
			"TriggerType": "ContaminatedTrigger",
			"Data": { 
				"Pos": [ 4024, 0, 11782],
				"Radius": 100,
				"PosHeight": 22,
				"NegHeight": 2,
				"InnerRingCount": 1,
				"InnerPartDist": 50,
				"OuterRingToggle": 1, 
				"OuterPartDist": 60, 
				"OuterOffset": 0, 
				"VerticalLayers": 0,
				"VerticalOffset": 0,
				"ParticleName": "graphics/particles/contaminated_area_gas_bigass"
				},
			"PlayerData": {
				"AroundPartName": "graphics/particles/contaminated_area_gas_around",
				"TinyPartName": "graphics/particles/contaminated_area_gas_around_tiny",
				"PPERequesterType": "PPERequester_ContaminatedAreaTint"
			}
		},
 
 
 
 
 Thanks, Rob.
