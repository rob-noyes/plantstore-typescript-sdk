# Reference

## plant

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">addPlant</a>({ ...params }) -> RobertNoyesDemoApi.PlantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.addPlant({
    name: "Fern",
    category: "Indoor",
    tags: ["green", "leafy"],
    status: "available",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.Plant`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">updatePlant</a>({ ...params }) -> RobertNoyesDemoApi.PlantResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.updatePlant({
    name: "Fern",
    category: "Indoor",
    tags: ["green", "leafy"],
    status: "sold",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.Plant`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">searchPlantsByStatus</a>({ ...params }) -> RobertNoyesDemoApi.PlantResponse[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Filter plants based on their current status.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.searchPlantsByStatus();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.SearchPlantsByStatusRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">searchPlantsByTags</a>({ ...params }) -> RobertNoyesDemoApi.PlantResponse[]</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Filter plants based on associated tags.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.searchPlantsByTags();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.SearchPlantsByTagsRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.plant.<a href="/src/api/resources/plant/client/Client.ts">getPlantById</a>({ ...params }) -> RobertNoyesDemoApi.PlantResponse</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve a plant's details by its ID.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.plant.getPlantById({
    plantId: 1,
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.GetPlantByIdRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `Plant.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

## user

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">loginUser</a>({ ...params }) -> RobertNoyesDemoApi.UserAuthResponse</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.loginUser();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.LoginUserRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">logoutUser</a>() -> void</code></summary>
<dl>
<dd>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.logoutUser();
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>

<details><summary><code>client.user.<a href="/src/api/resources/user/client/Client.ts">getUserByName</a>({ ...params }) -> RobertNoyesDemoApi.User</code></summary>
<dl>
<dd>

#### 📝 Description

<dl>
<dd>

<dl>
<dd>

Retrieve user details using their username.

</dd>
</dl>
</dd>
</dl>

#### 🔌 Usage

<dl>
<dd>

<dl>
<dd>

```typescript
await client.user.getUserByName({
    username: "username",
});
```

</dd>
</dl>
</dd>
</dl>

#### ⚙️ Parameters

<dl>
<dd>

<dl>
<dd>

**request:** `RobertNoyesDemoApi.GetUserByNameRequest`

</dd>
</dl>

<dl>
<dd>

**requestOptions:** `User.RequestOptions`

</dd>
</dl>
</dd>
</dl>

</dd>
</dl>
</details>
